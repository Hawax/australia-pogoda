# Przewidywanie opadów deszczu - Modelowanie i analiza danych

Ten projekt ma na celu przewidywanie opadów deszczu na podstawie różnych cech pogodowych. Wykorzystuje on trzy różne modele uczenia maszynowego: RandomForestClassifier, GradientBoostingClassifier i sieć neuronową, aby przewidzieć, czy następnego dnia będzie padać deszcz.

## Opis projektu

Projekt składa się z następujących kroków:
1. Wczytanie i przygotowanie danych
2. Preprocessing danych
   - Usunięcie niepotrzebnych kolumn
   - Wypełnienie brakujących wartości
   - Kodowanie zmiennych kategorycznych
   - Skalowanie cech
   - Zastosowanie PCA do redukcji wymiarowości
3. Eksploracyjna analiza danych (EDA)
   - Macierz korelacji
   - Wybór odpowiednich cech
4. Podział danych na zbiór treningowy i testowy
5. Trenowanie modeli
   - RandomForestClassifier
   - GradientBoostingClassifier
   - Sieć neuronowa (z użyciem Tensorflow i Keras)
6. Ocena modeli
   - Dokładność na zbiorze treningowym i testowym
   - Macierze pomyłek
   - Porównanie dokładności różnych modeli
7. Wizualizacja wyników
   - Wykres strat sieci neuronowej
   - Wykresy dokładności dla różnych modeli

## Wymagania

- Python 3.x
- Biblioteki: pandas, numpy, scikit-learn, tensorflow, keras, matplotlib, seaborn
