## Zadanie dot. zmiennego rozmiaru obrazków w danych wejściowych

Celem zadania jest przeanalizowanie i zastosowanie metod na trening sieci neuronowej w przypadku gdy obrazki w zbiorze danych mają różny rozmiar.
W pracy domowej należy:
1. znaleźć zbiór z obrazkami o różnym wymiarze albo zmodyfikować zbiór, który ma obrazki o jednakowym rozmiarze
2. rozwiązać problem różniących się wymiarów z użyciem keras ImageDataGenerator (omawianego na zajęciach) - na czym polega na metoda, następnie wytrenować sieć konwolucyjną
3. wytrenować sieć neuronową na niezmienionych obrazkach przy czym wówczas należy zmienić architekturę sieci neuronowej uwzględniając warstwę Global Pooling 
  (w wersji average lub max). Proszę:
  - opisać krótko jak ta warstwa neuronowa działa i dlaczego w tym problemie znajduje zastosowanie
  - odpowiedzieć na pytanie czy batch_size w tym rozwiązaniu może być dowolny
 4. opisać wady/zalety dwóch metod

Inne pomysły na rozwiązanie tego problemu są mile widziane, wówczas można je zaprezentować zamiast podejścia z Global Pooling.

Termin oddania mija 8 czerwca o 23:59.

Rozwiązania (Jupyter Notebook) proszę zgłaszać przez pull request do podfolderu z imieniem i nazwiskiem.
