# GermanWordsNLP - Analiza Częstotliwości Słów w Języku Niemieckim

Projekt realizuje analizę częstotliwości występowania słów w tekstach niemieckich oraz ich zgodności z prawem Zipfa. Program przetwarza dane tekstowe, generuje statystyki oraz wizualizuje wyniki.

## Funkcjonalności
1. **Wczytywanie plików**: Analizowane są pliki tekstowe w folderze `deutchesPDF`.
2. **Przetwarzanie tekstu**: Czyszczenie danych, tokenizacja oraz agregacja liczby wystąpień słów.
3. **Analiza zgodności z prawem Zipfa**: Wyznaczanie teoretycznych częstotliwości na podstawie pozycji słowa w rankingu.
4. **Wizualizacja wyników**: Generowanie wykresu porównującego rzeczywiste i przewidywane częstotliwości.

## Wymagania
- Python 3.9 lub nowszy
- Zainstalowane biblioteki:
  - `pandas`
  - `matplotlib`

## Instrukcja uruchomienia
1. Upewnij się, że wszystkie pliki tekstowe znajdują się w folderze `data_txt`.
2. Zainstaluj wymagane biblioteki:
   ```bash
   pip install -r requirements.txt

3. Uruchom jupyter notebook lub google collab
    ```bash
   jupyter notebook

4. Prześlij plik
  ```python
  zipf (4).ipynb

