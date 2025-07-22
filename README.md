"# Analiza-Mundialu" 

**Autor:** Hubert Gogola  
**Data:** 03.12.2024  
**Tytuł:** Analiza Mistrzostw Świata w Piłce Nożnej

---

## 📌 Opis projektu

Projekt przedstawia kompleksową analizę statystyczną danych z Mistrzostw Świata w Piłce Nożnej rozgrywanych w latach 1930–2022. Analizie poddano zmienne takie jak liczba drużyn, liczba meczów, liczba bramek, średnia liczba goli na mecz, sukcesy poszczególnych reprezentacji, wpływ gospodarzy oraz dominacja kontynentów.

Dane zostały pobrane z Kaggle:  
🔗 [FIFA Football World Cup Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/fifa-football-world-cup-dataset)

---

## 📁 Struktura projektu

## 🛠️ Wykorzystane narzędzia

Analiza została przeprowadzona w języku **R** przy użyciu następujących pakietów:

```r
library(dplyr)
library(ggplot2)
library(reshape2)
library(tidyr)
library(treemapify)
library(magrittr)
library(ggcorrplot)
```
📊 Zakres analizy
🔍 Wstępna eksploracja danych
Sprawdzenie struktury i typu danych

Statystyki opisowe i identyfikacja wartości odstających

Sprawdzenie brakujących danych

📈 Trendy w czasie
Zmiana liczby drużyn, meczów i goli od 1930 do 2022 roku

Analiza średniej liczby goli na mecz

Wpływ nowoczesnej piłki na styl gry i strategię

🏆 Sukcesy reprezentacji
Klasyfikacja krajów wg liczby zdobytych tytułów mistrzowskich

Analiza krajów zajmujących 2. i 3. miejsca

Pozycja Polski na tle innych drużyn

🏠 Gospodarze turnieju
Czy organizatorzy mają większe szanse na sukces?

Porównanie średniej liczby goli między gospodarzami a gośćmi

Wpływ lokalizacji turnieju na końcowe wyniki

🌍 Kontynenty w mistrzostwach świata
Dominujące kontynenty jako gospodarze i mistrzowie

Analiza rozkładu sukcesów według regionów geograficznych

🔥 Korelacje danych
Heatmapa korelacji pomiędzy kluczowymi zmiennymi liczbowymi

Identyfikacja najsilniejszych zależności (np. rok vs liczba drużyn)

📌 Najciekawsze wnioski
Europa i Ameryka Południowa zdominowały zarówno organizację, jak i wygrywanie mundiali.

Liczba drużyn, meczów i goli rosła z biegiem lat, ale średnia liczba goli na mecz spadła i ustabilizowała się na poziomie ~2.5.

Gospodarze częściej zdobywają medale, ale sukces nie jest gwarantowany.

Brazylia jest liderem wszech czasów z 5 tytułami mistrza świata.

W analizie korelacji zauważono, że liczba meczów i drużyn silnie koreluje z rokiem, co potwierdza rozwój turnieju.

📄 Źródło danych
Dane użyte w analizie pochodzą z publicznie dostępnego źródła na platformie Kaggle:
FIFA Football World Cup Dataset

📌 Uruchomienie projektu
Aby uruchomić projekt lokalnie:

Upewnij się, że masz zainstalowane R i RStudio.

Otwórz plik Analiza-Mundialu.Rmd w RStudio.

Uruchom kod sekcja po sekcji lub wygeneruj raport HTML klikając Knit.

📬 Kontakt
Jeśli masz pytania dotyczące projektu, możesz skontaktować się z autorem:

Hubert Gogola

📚 Licencja
Projekt edukacyjny – wolny do użytku niekomercyjnego. Dane pochodzą z Kaggle i są udostępniane zgodnie z ich polityką.

