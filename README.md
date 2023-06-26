# ***DermaMNIST Classification*** - klasyfikacja podzbioru z bazy MedMNIST

***Cel zadania:*** 
Opracować procedurę złożoną z przetwarzania wstępnego oraz klasyfikacji danych w celu uzyskania jak najlepszych wyników klasyfikacji dla zadanego zbioru danych.
******************

*Zadanie domowe z przedmiotu "Uczenie Maszynowe" na studiach Inżynieria Biomedyczna, specjalizacja: Sztuczna Inteligencja.*

Zadanie miało na celu preprocessing oraz klasyfikację danych ze zbioru DermaMNIST ([link do zbioru](https://medmnist.com/)) nie używając sieci konwolucyjnych, rekurencyjnych ani transformerów. Dodatkowo, nie można było korzystać z zespołu różnych modeli. 

Do wykonania preprocessingu sugerowano się wiedzą własną oraz [notatnikiem ze strony Kaggle](https://www.kaggle.com/code/benyaminghahremani/dermatology-mnist-classification-cnn). Ze względu na ograniczenia projektowe do klasyfikacji wybrano *RandomForestClassifier*, rozpatrywano również klasyfikatory *SVM* oraz *DecisionTreeClassifier* aczkolwiek nie uzyskano dla nich satysfakcjonujących wyników (**accuracy** ~ 60%, **f1_score** ~ 60%).
******************

Uzyskane wartości dla **RandomForrestClassifier**: 
* accuracy = 72%
* f1_score = 70%

Macierz pomyłek: </br>

![obraz](https://github.com/natrendt/MedMNIST/assets/83702845/df839555-8146-4d83-a3ef-d645538f8b2a)

TO DO:
* dodać opis po angielsku w pliku *readme.md*
* wybróbować inne podejścia w preprocessingu danych
* przetestować działanie innych klasyfikatorów 
