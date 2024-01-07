## Zasady konkursu SRD
### Zespoły
Należy dobrać się w zespoły złożone z maksymalnie 3 osób. Proszę nazwać zespół (nazwa zespołu pojawi się w tabeli z wynikami). Proszę nie używać danych osobowych w nazwach.

### Zbiór danych i cel konkursu
Celem konkursu jest uzyskanie jak największego:
* Grupy 12,14,16 - [**F1-Score**](https://en.wikipedia.org/wiki/F-score)
* Grupy 11,13,15 - [**Accuracy**](https://en.wikipedia.org/wiki/Accuracy_and_precision#In_binary_classification)

w klasyfikacji zmiennej celu **IsIPA**. Do stworzenia i optymalizacji modelu proszę wykorzystać zbiór danych **IPA.csv**, natomiast finalną predykcję należy wykonać na zbiorze **IPA_test.csv**. Opis zbioru znajduje się w pliku **IPA_description.txt**.


### Wyniki
Wyniki należy przesłać na adres **lkrain@sgh.waw.pl** do końca zajęć danej grupy. W treści maila należy podać nazwę grupy oraz imiona i nazwiska członków - wystarczy mail od jednego członka grupy.

Jako załączniki należy zamieścić:
1. Skrypt/notatnik z wykorzystanym kodem (w dowolnym języku programowania)
2. Plik CSV o nazwie **[nazwa_grupy]_prediction.csv** zawierający jedną kolumnę z 5000 obserwacji (i opcjonalnym nagłówkiem) z wartościami 1/0 lub TRUE/FALSE oznaczających predykcję dla kolejnych wierszy ze zbioru testowego **IPA_test.csv**.

Proszę sprawdzić czy kolejność predykcji zgadza się z kolejnością obserwacji w zbiorze testowym. Proszę również zwrócić uwagę na braki danych w zbiorze testowym - należy je odpowiednio obsłużyć tak, aby otrzymać dokładnie 5000 predykcji.

Tabela z rankingiem zespołów pojawi się na GitHubie w poniższym pliku README. Najlepszy zespół w każdej grupie zajęciowej otrzyma dodatkowe 5 punktów, kolejny 4 punkty, itd.

Życzę powodzenia.

### Wyniki konkursu

Grupa 12
| **Zespół**          | **F1-score** | **Punkty** | **Język** | **Model**              |
|---------------------|--------------|------------|-----------|------------------------|
| Statystyczne Świrki | 79,02        | 5          | Python    | XGBoost                |
| Ananas              | 78,99        | 4          | Python    | XGBoost                |
| Nazwa               | 78,33        | 3          | Python    | Gradient Boosted Trees |
| JRK                 | 77,94        | 2          | Python    | XGBoost                |
| Jakoś to będzie     | 77,87        | 1          | Python    | Random Forest          |
| Analityczne Kotki   | 77,81        | 0          | Python    | Gradient Boosted Trees |
| StudentDe           | 77,24        | 0          | Python    | Gradient Boosted Trees |
| Bałwanki            | 76,88        | 0          | Python    | CART                   |

Grupa 14
| **Zespół**              | **F1-score** | **Punkty** | **Język** | **Model**                 |
|-------------------------|--------------|------------|-----------|---------------------------|
| Trzej Muszkieterowie    | 79,14        | 5          | Python    | XGBoost                   |
| Renifery                | 78,55        | 4          | Python    | XGBoost                   |
| Snorlax                 | 77,92        | 3          | Python    | XGBoost                   |
| Pizza z Pierwszej Ławki | 77,86        | 2          | Python    | Gradient Boosted Trees    |
| 3A                      | 77,80         | 1          | Python    | Gradient Boosted Trees    |
| Grupa 16                | 75,63        | 0          | Python    | Support Vector Classifier |

Grupa 16
| **Zespół**           | **F1-score** | **Punkty** | **Język** | **Model**     |
|----------------------|--------------|------------|-----------|---------------|
| Skład Węgla i Papy   | 78,88        | 5          | Python    | Random Forest |
| Chleb                | 78,81        | 4          | Python    | XGBoost       |
| Trzej Muszkieterowie | 78,09        | 3          | Python    | Random Forest |
| Smerfy               | 77,94        | 2          | Python    | Random Forest |
| MWM                  | 77,82        | 1          | Python    | Random Forest |
| Panda 5              | 75,54        | 0          | Python    | XGBoost       |
| Pryncypałki          | 43,33        | 0          | Python    | Random Forest |
