## Zadanie - warstwa konwolucyjna w praktyce
Celem zadania jest poznanie różnych metod implementowania operacji konwolucji w sieciach neuronowych.
Jedna z metod została omówiona na zajęcia, druga wymaga aby studenci znaleźli informacje w dostępnych źródłach.

Należy napisać dwie funkcje:
- implementującą operację w ramach warstwy konwolucyjnej w sposób omówiony na zajęciach ("filtr jest przesuwany wzdłuż obrazka")
    - dla obrazków czarno-białych
    - dla obrazków RGB
    - z uwzględnieniem, że może być zastosowanych kilka filtrów oraz parametrem *stride*
- implementującą operację konwolucji jako mnożenie macierzy (podpowiedź: jednym z podejść jest zastosowanie *im2col*)
    - można się ograniczyć do obrazków czarno-białych
    - z uwzględnieniem, że może być zastosowanych kilka filtrów
    
Filtry można zainicjalizować losowo.

Aby wykazać, że zaimplementowana funkcja jest poprawna warto wziąć dowolną grafikę ilustrujacą operację konwolucji gdzie podane są wartości w danych wejściowych, filtrze i danych wyjściowych i sprawdzić czy nasza funkcja zwróci takie same wartości.

Należy porównać czas wykonania dwóch funkcji na przykładzie i sformułować wnioski.

Termin oddania mija w momencie rozpoczęcia zajęć w dniu 25 marca br.

Rozwiązania (Jupyter Notebook) proszę zgłaszać przez pull request do podfolderu z imieniem i nazwiskiem.

