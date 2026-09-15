PQK-SVM---Apple-Tesla-Microsoft
Algorytm PQK-SVM zajmujący się predykcją cen akcji przy użyciu czynników makroekonomicznych. 
Krok po kroku:

* **Zbieranie danych rynkowych**: Pobieramy historyczne dane dla wybranych spółek (Apple, Microsoft, Tesla) oraz kluczowe wskaźniki makroekonomiczne i rynkowe, takie jak zmienność (VIX), rentowność obligacji (US10Y), złoto czy indeks dolara (DXY).
* **Przetwarzanie i inżynieria cech**: Przekształcamy surowe dane w stopy zwrotu oraz stosujemy zaawansowane metody (np. różniczkowanie ułamkowe), aby odpowiednio przygotować je do modeli analitycznych bez utraty pamięci historycznej szeregu czasowego.
* **Kwantowe jądra danych (Quantum Kernel Methods)**: Zamiast klasycznych algorytmów, rzutujemy dane rynkowe do wielowymiarowej przestrzeni Hilberta za pomocą obwodów kwantowych. Pozwala to na uchwycenie nieliniowych zależności między wskaźnikami makro a zachowaniem cen akcji.
* **Testowanie horyzontów czasowych**: Sprawdzamy skuteczność predykcji (kierunku ruchu ceny) w różnych horyzontach – krótko-, średnio- i długoterminowych (np. 5, 10 i 21 dni do przodu).
* **Testy na prawdziwym QPU (Odra 5)**: Badamy, jak nasze obwody kwantowe zachowują się w rzeczywistości. Uruchamiamy obliczenia na fizycznym procesorze kwantowym Odra 5, testując wpływ liczby powtórzeń (shots) na stabilność wyników i odporność na szum sprzętowy.

Czy w takim ujęciu narracyjnym chcesz coś zmodyfikować lub położyć większy nacisk na konkretny aspekt projektu?
