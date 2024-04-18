# projekt-analiza-danych

Cel projektu:
Celem projektu była analiza danych pod kątem wyznaczenia cech, klasyfikacji przy użyciu różnych algorytmów oraz zestawienia wykresów przy pomocy oprogramowania Orange, jak również wysnucia własnych wniosków.

Zestaw Danych
Jako zestaw danych wybrałem „Pima Indians Diabetes Database” ze strony kaggle.com. Celem zbioru, na podstawie pomiarów diagnostycznych, jest wyznaczenie czy pacjent ma cykrzycę czy nie. Grupą badanych ludzi są kobiety w wieku nie mniejszym niż 21 lat o pochodzeniu natywnych amerykanów z plemienia „Pima”. 
Link do zestawu: kaggle.com/datasets/uciml/pima-indians-diabetes-database/data
Zbiór danych składa się z kilku medycznych zmiennych prognostycznych i jednej zmiennej docelowej:
a) Do zmiennych prognostycznych zaliczamy (wszystkie zmienne są numeryczne):
- Insulin: 2-godzinna insulina w surowicy (mu U/ml)
- Glukose: stężenie glukozy w osoczu po 2 godzinach w doustnym teście tolerancji glukozy     (mm Hg)
- Pregnancies:  liczba zajść w ciążę
- BloodPressure: rozkurczowe ciśnienie krwi (mm/Hg)
- SkinThickness: grubość fałdu skórnego mięśnia trójgłowego uda (mm)
- BMI: wskaźnik masy ciała (waga w kg/(wzrost w m)^2)
- DiabetesPedigreeFunction: Funkcja rodowodu cukrzycy
- Age: Wiek (lata)
b) Do zmiennej docelowej zaliczamy: 
- Output: zmienna klasy (0 – nie chory lub 1 - chory)

Podstawowe dane zbioru:
Średnia wieku: 30 lat, minimalny: 21, maksymalny: 81
Średni poziom glukozy: 122, minimalny: 55, maksymalny: 198
Średni poziom insuliny: 156, minimalny: 14, maksymalny: 846
Średnie BMI: 33, minimalne: 18.2, maksymalne: 67.1