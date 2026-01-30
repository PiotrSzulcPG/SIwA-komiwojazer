# SIwA-komiwojazer

## Treść zadania
Zadanie do wykonania polega na zastosowaniu algorytmu symulowanego wyżarzania [1] do problemu komiwojażera [2] w języku python. Można korzystać z dowolnych bibliotek dostępnych w języku python. Zadanie należy oddać w formie sprawozdania z wytłumaczeniem kluczowych elementów programu (przykładowo wczytanie danych, algorytm, wizualizacja) oraz kodu źródłowego. Wyniki należy zobrazować oraz podać wnioski. Należy skorzystać z danych zamieszczonych pod adresem [3] (przykładowo xqf131), do rozpakowania danych można skorzystać z biblioteki [4].
[1] https://www.geeksforgeeks.org/dsa/implement-simulated-annealing-in-python/  
[2] https://pl.wikipedia.org/wiki/Problem_komiwoja%C5%BCera  
[3] https://www.math.uwaterloo.ca/tsp/vlsi/index.html  
[4] https://tsplib95.readthedocs.io/en/stable/pages/usage.html  

## Prerequisites
* Python (testowane na 3.13) [(Możesz pobrać tutaj)](https://www.python.org/downloads/).  
* Jupyter Notebook (`pip install notebook`) lub [VSCode](https://code.visualstudio.com/) z zainstalowanym [Jupyter Notebook](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
 
## instalacja

1. **Sklonuj repozytorium**
```bash
git clone https://github.com/twoj-uzytkownik/twoje-repozytorium.git
cd twoje-repozytorium

```

Struktura folderów:

```
├── data/                # Przykładowe pliki danych TSP (.tsp)
│   ├── xqf131.tsp
│   ├── ...
├── komiwojazer.ipynb    # Notebook z kodem i opisem
├── README.md            # Ten plik
```
2. **Zaintaluj biblioteki**

```bash
pip install tsplib95 simanneal matplotlib numpy
```

3. **Uruchom plik**
Możesz uruchomić notebook w Jupyter:

```bash
jupyter notebook komiwojazer.ipynb
```

lub w VS Code (otwórz plik komiwojazer.ipynb i uruchamiaj komórki).


## Uwagi
Kod oraz wnioski znajdują się w pliku [komiwojazer.ipynb](komiwojazer.ipynb)
