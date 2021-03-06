# -Programowanie_zespolowe_2018_gr3

## Wirtualna uczelnia napisana w JavaFX
Nasza aplikacja będzie miała za zadanie obsługiwanie pracowników oraz studentów uczelni.
Dzięki aplikacji będziemy mieli możliwość :
- dodawać, usuwać edytować i sprawdzać plan zajęć
- dodawać, usuwać edytować i sprawdzać listę studentów i prowadzących zajęcia
- przydzielać studentom prowadzących zajęcia
- przydzielać przedmioty do prowadzącego
- generować PDF z ocenami dla ucznia i prowadzącego
- wyświetlenia planu zajęć przy użyciu kalendarza oraz tabeli
## Aplikacja będzie posiadać 4 grupy użytkowników :
- student : z dostępem do sprawdzania ocen, planu zajęć, danych osobowych oraz
generowania ocen do PDF
- prowadzący: z dostępem do wprowadzania i zmiany ocen, generowania ich do PDF,
planu zajęć
- dziekanat: z dostępem do modyfikacji planu zajęć, dodawania i wyszukiwania
studentów, przydzielania im prowadzących oraz wyświetlania i modyfikacji danych
studenta(dane osobowe, oceny)
- administrator : nadaje uprawnienia, zarządza całym systemem oraz ma dostęp do
wszystkich funkcji dostępnych dla pozostałych użytkowników
## Do zrealizowania projektu użyjemy następujących narzędzi:
- Jira- narzędzie do organizowania pracy i obowiązków
- Github - narzędzie do publikowania napisanego kodu
- Java - język programowania, w którym powstanie projekt
- MariaDB - narzędzie do tworzenia bazy danych

## Schemat UML 

![alt text](https://github.com/mjochab/-Programowanie_zespolowe_2018_gr3/blob/master/UML.PNG)


## Wygląd okna logowania:
- okno będzie zawierać 2 komunikaty (Label) Login i Hasło
- przycisk (Button) Zaloguj!
- jedno pole do wpisywania (TextField) username
- jedno szyfrowane pole do wpisywania (PasswordField) password


## Wygląd okna studenta:
- okno zawierać będzie przycisk do wylogowania użytkownika
- przycisk do sprawdzenia ocen
- przycisk do sprawdzania Planu zajęc dla zalogowanego studenta
- przyciska przekierowujący do sceny z danymi osobowymi
- wyświetlana będzie nazwa użytkownika (imie, nazwisko, nr albumu)

## Wygląd Okna Planu zajęć dla studenta
- wyświetla w tabeli informacje o terminie i rodzaju zajęć
- zawiera przyciski pozwalające na wyświetlanie zajęć na kolejne tygodnie 
- przycisk Menu do sekcji z oknem menu studenta
- przyciski do zamknięcia aplikacji oraz wylogowania użytkownia

## Wygląd Okna dane osobowe
- umożliwa sprawdzenie studentowi swoich danych personalnych i modyfikacje ich
- zawiera przycisk do zapisu zmienionych danycyh użytkownika
- standardowe przyciski do poruszania się po aplikacji (Menu, Wyloguj, Zamknij)

## Wygląd Okna Ocen dla studenta
- w tabeli otrzymujemy informacje przedmiotach oraz jakie ocene otrzymaliśmy u danego prowadzącego oraz liczbie godzin
- przycisk umożliwające wygenerowanie ocen w PDF
- standardowe przyciski do poruszania się po aplikacji (Menu, Wyloguj, Zamknij)


## Wygląd okna Administratora:
- okno zawierać będzie przycisko do wylogowania
- przycisk do sekcji Użytkownicy (edycja użytkowników)
- Przycisk do sekcji Plan zajęć (edycja planów zajęć)
- Przycisk do sekcji z historią logowań użytkowników
- przycisk do sekcji Oceny (edycja, przepisywanie ocen)

## Wygląd okna Dziekanatu:
- okno zawierać będzie przycisko do wylogowania
- przycisk do sekcji Użytkownicy (edycja użytkowników)
- Przycisk do sekcji Plan zajęć (edycja planów zajęć)
- przycisk do sekcji Oceny (edycja, przepisywanie ocen)


## Wygląd okna Wykładowcy:
- okno zawierać będzie przycisko do wylogowania
- Przycisk do sekcji Plan zajęć (edycja planów zajęć)
- przycisk do sekcji Oceny (edycja, przepisywanie ocen)

## Wygląd okna Plan zajęć dla wykładowcy
- wyświetla w tabeli informacje o terminie i rodzaju zajęć
- zawiera przyciski pozwalające na wyświetlanie zajęć na kolejne tygodnie 
- standardowe przyciski do poruszania się po aplikacji (Menu, Wyloguj, Zamknij)

## Wygląd okna Oceny dla wykładowcy
- Wyświetla w tabeli wpisane oceny
- zawiera przyciski oraz pola umożliwiajace wprowadzania ocen studentom, edycje orazu usuwanie ich
- możliwość wygenerowania tabeli z ocenami
- standardowe przyciski do poruszania się po aplikacji (Menu, Wyloguj, Zamknij)



## Diagram ERD 
![alt text](https://github.com/mjochab/-Programowanie_zespolowe_2018_gr3/blob/master/30713038_1819959841376505_2636789429284372480_n.jpg)
