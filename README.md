# 🪙 bitcoin-price-prediction

## ✨ Prognozowanie cen Bitcoina z wykorzystaniem LSTM

Kompletny pipeline do prognozowania cen Bitcoina na podstawie danych historycznych, wykorzystujący sieci neuronowe LSTM (Long Short-Term Memory) w Pythonie. 📈🤖

---

## 📦 Zawartość projektu

- Pobieranie danych o cenach Bitcoina z Yahoo Finance (`yfinance`) 🏦
- Analiza i wizualizacja danych historycznych (`pandas`, `matplotlib`) 📊
- Przygotowanie danych do modelowania (normalizacja, sekwencje czasowe) 🔄
- Budowa i trenowanie zaawansowanego modelu LSTM (`TensorFlow`, `Keras`) 🧠
- Ewaluacja modelu i analiza błędów predykcji 📉
- Prognoza ceny Bitcoina na najbliższy dzień i okres 10 dni 🗓️
- Testowanie skuteczności modelu na danych historycznych 🔍

---

## 🚀 Jak uruchomić projekt?

1. **Klonuj repozytorium:**
   ```bash
   git clone https://github.com/username/bitcoin-price-prediction.git
   cd bitcoin-price-prediction
   ```

2. **Zainstaluj wymagane biblioteki:**
   ```bash
   pip install numpy pandas matplotlib tensorflow yfinance scikit-learn seaborn
   ```

3. **Uruchom notebook:**
   - Otwórz plik `notebook.ipynb` w Jupyter Notebook lub VS Code.

---

## 📚 Wymagane biblioteki

- numpy
- pandas
- matplotlib
- seaborn
- tensorflow
- keras
- yfinance
- scikit-learn

---

## 📝 Opis działania

1. **Import bibliotek** 📚  
   Import wszystkich niezbędnych narzędzi do analizy, wizualizacji i budowy modelu LSTM.

2. **Pobieranie danych** 📥  
   Pobranie historycznych cen Bitcoina z Yahoo Finance od 2015 roku do dnia obecnego.

3. **Eksploracja danych** 🔍  
   Analiza podstawowych statystyk i trendów w danych historycznych Bitcoina.

4. **Przygotowanie danych** ⚙️  
   Normalizacja cen i tworzenie sekwencji czasowych (okien) do uczenia modelu LSTM.

5. **Budowa i trenowanie modelu** 🧠  
   Tworzenie i trenowanie zaawansowanego modelu LSTM z wieloma warstwami i mechanizmami regulacji.

6. **Ewaluacja modelu** 📊  
   Obliczanie metryk (MSE, MAE, RMSE, R2) i analiza dokładności predykcji.

7. **Wizualizacja wyników** 🖼️  
   Porównanie rzeczywistych i prognozowanych cen Bitcoina na wykresach.

8. **Prognozy krótkoterminowe** 📈  
   Wyznaczenie prognozowanej ceny Bitcoina na najbliższy dzień.

9. **Prognozy średnioterminowe** 📆  
   Prognoza cen Bitcoina na kolejne 10 dni wraz z wizualizacją.

10. **Testowanie historyczne** ⏱️  
    Weryfikacja skuteczności modelu na wybranych okresach historycznych.

---

## 🔍 Metodologia

- **Preprocessing danych** - Normalizacja cen do zakresu [0,1] dla lepszej zbieżności modelu
- **Sekwencje czasowe** - Wykorzystanie 14-dniowych okien do predykcji kolejnego dnia
- **Architektura modelu** - Wielowarstwowy LSTM z Dropout i BatchNormalization
- **Regularyzacja** - Zastosowanie mechanizmów przeciwdziałających przeuczeniu
- **Metryki** - Wykorzystanie MSE, MAE, RMSE i R2 do oceny jakości modelu

---

## 📈 Wyniki

Model LSTM jest zdolny do:
- Precyzyjnego przewidywania kierunku zmian ceny Bitcoina
- Identyfikacji potencjalnych punktów zwrotnych
- Generowania wiarygodnych prognoz krótkoterminowych z błędem MAPE na poziomie kilku procent
- Śledzenia trendów i sezonowości w danych historycznych

---

## 🔮 Zastosowania

- **Analiza inwestycyjna** - Wsparcie decyzji inwestycyjnych na rynku kryptowalut
- **Zarządzanie ryzykiem** - Oszacowanie potencjalnej zmienności cen Bitcoina
- **Edukacja** - Demonstracja zastosowania głębokich sieci neuronowych w prognozowaniu rynków finansowych

---

## ⚠️ Zastrzeżenia

Projekt ma charakter edukacyjny. Prognozy generowane przez model nie powinny być jedyną podstawą decyzji inwestycyjnych. Rynek kryptowalut charakteryzuje się wysoką zmiennością i jest podatny na czynniki zewnętrzne, których model może nie uwzględniać.

---

## 👤 Autor

[github.com/LiCHUTKO](https://github.com/LiCHUTKO)

---

## ⭐️ Jeśli projekt Ci się podoba, zostaw ⭐️!
