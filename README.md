# Zastosowanie metod uczenia maszynowego do binarnej klasyfikacji zagrożeń w systemach informatycznych: ocena skuteczności wybranych algorytmów

Repozytorium zawiera kod źródłowy stanowiący część praktyczną pracy magisterskiej. Celem projektu jest ewaluacja wybranych algorytmów uczenia maszynowego pod kątem ich skuteczności w wykrywaniu cyberataków w ruchu sieciowym oraz porównanie dwóch zbiorów danych.

## Wykorzystane Zbiory Danych
Badania przeprowadzono na dwóch popularnych zbiorach danych, pozwalających na rzetelną ocenę skuteczności modeli:
* Zbiór danych **UNSW-NB15**
* Zbiór danych z platformy **Kaggle**

## Struktura Repozytorium
Projekt został podzielony na 4 główne notatniki stworzone w środowisku Google Colab:

* `01_cybersec_eda_and_preprocessing.ipynb` – czyszczenie zbioru z Kaggle, One-Hot Encoding, skalowanie cech, podział na podzbiory.
* `02_cybersec_model_training_and_evaluation.ipynb` – trenowanie i testowanie modeli na zbiorze z Kaggle.
* `01_UNSW_NB15_cybersec_eda_and_preprocessing.ipynb` – czyszczenie zbioru UNSW-NB15, One-Hot Encoding, skalowanie cech, podział na podzbiory.
* `02_UNSW_NB15_cybersec_model_training_and_evaluation.ipynb` – trenowanie i testowanie modeli na zbiorze UNSW-NB15.
