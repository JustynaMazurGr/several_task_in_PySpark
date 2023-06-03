# several_task_in_PySpark

## Task
Based on the dataset of financial fraud (fraudTrain) obtained from https://www.kaggle.com/datasets/kartik2112/fraud-detection:

* Perform basic descriptive statistics (min, max, avg) for a sample data frame for all numeric fields.
* Check whether women or men perform more transactions and which gender has a higher average transaction value.
* Check the average and number of transactions broken down by categories.
* Determine the city with the highest number of women.
* Determine the state with the fewest men.

## Task
* Assuming the data is from 2019-2020, check if any minors (<21 years old) have performed transactions. How many of them were there?
* Assuming the night is from 00:00 to 06:00, morning is from 06:00 to 12:00, noon is from 12:00 to 16:00, afternoon is from 16:00 to 21:00, and the rest is night - determine when the crimes were most frequently committed.
* How many months have passed between the first and last crime?

## Task
Using the Faker package: https://faker.readthedocs.io/en/master/
generate 10,000 JSON files containing:

* First Name
* Last Name
* Date of Birth
* Phone Number
* City

Read these files using Spark and check:
* The average length of a first name.
* The month in which the most people were born.

## Task:
Take the data from the Faker exercise.

* Save it to CSV files partitioned by city.
* Take one of the selected cities and save the date of birth data to a Python list. Sort this list and print it on the screen.

## Task
Using the payment fraud data (fraudTrain) and window functions:

* Calculate the average, minimum, and maximum transaction amounts in each state for each year.
* Print the three largest fraudulent transactions in each category.
************************************************************************************************

## Zadanie

Na podstawie zbiorów danych o oszustwach finansowych (fraudTrain) pobranych z https://www.kaggle.com/datasets/kartik2112/fraud-detection:

* Wykonaj podstawowe statystyki opisowe (min, max, avg) dla przykładowej
ramki danych dla wszystkich pól numerycznych
* Sprawdź czy kobiety czy mężczyźni wykonują więcej transakcji i która z płci
ma większą średnią wartość transakcji
* Sprawdź średnie i liczbę transakcji w rozbiciu na kategorie
* Sprawdź w którym mieście mieszka najwięcej kobiet
* Sprawdź w którym stanie mieszka najmniej mężczyzn

## Zadanie

* Zakładając, że dane są z lat 2019-2020, sprawdź czy jacyś niepełnoletni (<21
lat) wykonywali transakcje. Ile ich było?
* Zakładając, że noc to 00:00 – 06:00, ranek 06:00 – 12:00, południe 12:00 –
16:00, popołudnie 16:00 – 21:00, a reszta to noc – sprawdź kiedy najczęściej
popełniane były przestępstwa
* Jak dużo miesięcy upłynęło pomiędzy pierwszym a ostatnim przestępstwem?

## Zadanie

Korzystając z pakietu Faker: https://faker.readthedocs.io/en/master/
wygeneruj 10000 plików JSON zawierających:
* Imię
* Nazwisko
* Datę Urodzenia
* Nr telefonu
* Miasto

Odczytaj te pliki za pomocą Sparka i sprawdź:
* Średnią długość imienia
* Miesiąc w którym urodziło się najwięcej osób

## Zadanie: 

Weź dane z ćwiczenia o Fakerze.
* Zapisz je do plików csv partycjonowanych po mieście.
* Weź jedno z wybranych miast i zapisz dane o datach urodzenia do pythonowej
listy. Posortuj tę listę i wypisz ją na ekran

## Zadanie

Korzystając z danych o oszustwach płatniczych (fraudTrain) i funkcji okienkowych:
* Wyznacz średnią, min oraz max wysokości transakcji w każdym stanie w
każdym roku
* Wypisz trzy największe transakcje będące oszustwem w każdej kategorii
