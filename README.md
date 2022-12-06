<h1>Task 1</h1>
<h2>Subtask 1</h2>
<p>6 punktów 🤭</p>
<h2> Subtask 3</h2>
<p>Cześć! 🧡 Jestem Karolina i zdecydowałam się na udział w Challange, ponieważ chciałabym coś zmienić w swoim życiu zawodowym. Od stycznia obecnego roku jestem rekruterką IT, przez ten czas zdążyłam troszkę się dowiedzieć jakie są role i co ogólnie co się robi w tym IT 🙂
  
  Stwierdziłam, że pora na coś więcej, bo żeby coś zmienić to trzeba zacząć działać w tym kierunku, stąd też mój ruch i zapisanie się na Challange! W końcu od czegoś trzeba zacząć! 🥇
  
Moim celem jest rozpoczęcie pracy jako tester manualny! :smiley: Wszystkich dookoła zachęcam do pracy w IT, no i samą siebie też zachęciłam!
  
Jeżeli chodzi o moje oczekiwania to chciałabym się dowiedzieć od strony praktycznej na czym polega praca testera. Dodatkowo oczekuję, że zdobędę wiedzę i doświadczenie, no i oczywiście jakieś tipy na przyszłość jak wkroczyć w ten świat! ... I nie zwariować XD</p>
**Karolina** 😻

<h2>Subtask 4</h2>
Ad. 1 Aplikacja jest panelem do zarządzania graczami, meczami i do tworzenia raportów.

Ad. 2 Fukcjonalności aplikacji:

Podstrona "Strona główna":
- informacja o ilości graczy, meczy, ilości raportów i akcji
- skrót umożlwiający przeniesienie do slacka do kontaktu z dev
- możliwość dodania gracza
- wyświetlanie ostatnich aktywności

Podstrona "Gracze":
- wyświetlanie listy graczy
- wyszukiwanie w zakładce "gracze"
- pobieranie listy graczy w formacie csv
- możliwość wydrukowania listy graczy
- możliwość dopasowania wyświetlania poszczególnych kolumn w zakładce "gracze"
- możliwość filtrowania wyników tabeli
- możliwość przewijania listy graczy

Podstrona "English":
- zmiana wersji języka na angielski

Podstrona "Wyloguj":
- możliwość wylogowania się

Po kliknięciu w danego gracza:
- możliwość dokonania edycji danych gracza

Podstrona "Mecze":
- możliwość dodania meczu
- możliwość edytowania danego meczu
- możliwość dodania raportu
- możliwość rozpoczęcia meczu
- możliwość wyświetlenia listy zdarzeń

Podstrona "Raporty":
- możliwość dodania raportu
- możliwość edytowania poszczególnego raportu

Według mnie fukcjonalności w aplikacji są intuicyjne. 

Moje sugestie:
1. Zmieniłabym wyświetlanie się zakładki "Mecze" oraz "Raporty", ponieważ są one widoczne dopiero po kliknięciu na danego gracza, a moim zdaniem powinny być widoczne od razu po zalogowaniu się.
2. Dodatkowo w polu "Gracze" dodałabym wybór liczby wyświetlanych graczy (np. aby wyświetlana lista składała się z 15 lub 20 pozycji). 
3. W miejscu wyszukiwania graczy dodałabym filtry co do wyszukiwania np. odnośnie nazwiska, imienia itp.
4. Drukowanie w polu "Gracze" - zmieniłabym sposób drukowania, podział na kolumny byłby bardziej zrozumiały. 

Ad. 3 Interfejs aplikacji jest prosty, szata graficzna jest nieskomplikowana. Sam wygląd aplikacji mi się nie podoba.

Ad. 4 Aplikacja jest intuicyjna i nie ma problemu ze zrozumienieniem co należy kliknąć. Budowa aplikacji jest prosta i nie wymaga długiego poznawania.

Ad. 5 Zauważone błędy:

Mimo narzuconego języka polskiego część funkcjonalności wyświetla się po angielsku np. w pozycji Gracze wyszukiwarka jako Search lub ikony download, print, itp.

Gracze:
- po pobraniu pliku CSV z danymi graczy wyświetlają się niepoprawne (test object) oraz niekompletne dane (tylko z danej strony czyli do 10 pozycji).

Formularz edycji danych gracza:
- Pole "Imię" i "Nazwisko" -> możliwość wpisania liczb i innych znaków oprócz liter
- Pole "Telefon" -> możliwość wpisania liter
- Pole "Waga" i "Wzrost" -> możliwość wpisania nierealnych wartości (np. ujemnych)
- Pole "Data urodzenia" -> możliwość wpisania nierealnych wartości (np. bardzo przeszły czas)
- Po kliknięciu "Clear" nie usuwają się wprowadzone dane.

Formularz edycji meczu: 
- po zjechaniu w dół strony widoczna jest Lista zdarzeń -> w miejscu "Meta dane" wyświetlane są fragmenty kodu.
- po kliknięciu "Clear" nie usuwają się wprowadzone dane.
- Nie można dodawać ani edytować Listy zdarzeń w Edycji meczu.

Raporty:
- możliwość dodania raportu z przyszłą datą.


<h1>Task 2</h1>
<h2>Subtask 1 - Pisanie przypadków testowych na podstawie User Story</h2>
Link: https://docs.google.com/document/d/1NImyQviNlMwI4XrVgBHEFYqZykCPW3lu0rMbg1CrXjw/edit?usp=sharing

<h2>Subtask 2 - Pisanie przypadków testowych na podstawie "własnych doświadczeń"</h2>
Link: https://docs.google.com/document/d/1wQjlDn1JxseryFMVxMB_-fKt7VJ_lo8YD_BT6a0tj1s/edit?usp=sharing

<h2>Subtask 3 - Po co piszemy test case’y?</h2>

**Po co piszemy test case’y?**

- Test case’y piszemy w celu udokumentowania w jasny i przejrzysty sposób różne możliwości obsłużenia modułów w ramach danej aplikacji. 

- Dobrze przygotowane test case’y upewniają testerów w tym, że nie pominęli żadnej ważnej funkcjonalności w aplikacji.

- Dodatkowo przypadki testowe są pomocne w przypadku pisania raportów z przeprowadzonych testów po ich zakończeniu.

- Co ważne, dla nowo przyjętych testerów test case’y stanowią źródło informacji o samej aplikacji, jej funkcjonalnościach oraz działaniu. 

<h2> Subtask 4* Dla chętnych - Pisanie przypadków testowych na podstawie "własnych doświadczeń"</h2>
Link: https://docs.google.com/document/d/164lum8wfixR88mhimARGnkl_FtmL5E5n7eGDKlgOF60/edit?usp=sharing


<h1>Task 3</h1>
<h2>Subtask 1 - Utworzenie formatki do zgłaszania błędów systemu</h2>
Link: https://docs.google.com/document/d/147z2arUi5lEksBGCVgZ7hHMaC2E4KWtt4Q-fq5nMXqw/edit?usp=sharing

<h2>Subtask 2 - Testowanie według planów testów i raportowanie błędów</h2>
Link: https://docs.google.com/document/d/16OJ_e1svHgiTy7nsLeFyKooAMXqx4y9-JyIWJJkYqpw/edit?usp=sharing

<h2>Subtask 3 - Raport z wykonanych testów</h2>
Link: https://docs.google.com/document/d/1f1frvPV22I9oiWvWY_Qc5lZPbRsETe23UI06JZsm1eQ/edit?usp=sharing

<h2>Subtask 4* Dla chętnych - Sesja testów eksploracyjnych</h2>
Link: https://docs.google.com/document/d/1CknR6nF_Zg4zOYx8hCHcSHg6sTVAcTab7LOf6vR-vMs/edit?usp=sharing

<h1>Task 4</h1>
<h2>Subtask 1 - Utworzenie formatki do zgłaszania błędów systemu</h2>
Link: https://docs.google.com/document/d/1cYa9G0aQBPS5Q-gDo7pfVz2-7lNvVPA2AfhXDzqTwTM/edit?usp=sharing

<h2>Subtask 2 - Testowanie eksploracyjne i raportowanie błędów</h2>
Link: https://docs.google.com/document/d/1tGG7OrpU5Lw9WrNiw4UaBRPKDlsN5Z6-HRQfB2UGqms/edit?usp=sharing

<h2>Subtask 3 - Do czego służy ta aplikacja?</h2>

- *Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?*

Aplikacja służy do prowadzenia afirmacji i medytacji. Można w niej rozpocząć wyzwania związane z medytacją oraz prowadzić ćwiczenia oddechowe na podstawie wybranych kryteriów (czas, poziom zaawansowania). Aplikacja zawiera poradniki, które mają ułatwić prowadzenie praktyki medytacji. Dodatkowo można w niej znaleźć artykuły, podcasty tematyczne oraz muzykę czy dźwięki relaksujące.
Aplikacja ma na celu pomagać ludziom radzić sobie ze stresem, lękiem, bezsennością, rozkojarzeniem. Kolejnym celem jest zwiększenie wiedzy i świadomości w temacie praktyki oraz samorozwoju. 

- *Kto ma być użytkownikiem końcowym aplikacji?*

Użytkownikiem końcowym jest każda osoba, która chciałaby ćwiczyć oddech medytować, afirmować, odpoczywać efektywnie. Aplikacja skierowana jest do kobiet oraz mężczyzn. Można w niej znaleźć elementy dla osób początkujących, średniozaawansowanych oraz mocno zaawansowanych.

- *Czy według Ciebie aplikacja jest user friendly?*

Aplikacja jest user friendly, interfejs jest przejrzysty. Wchodząc do aplikacji po krótkim czasie wiadomo jak się po niej poruszać, gdzie są jakie funkcjonalności. Kolorystyka aplikacji jest spójna, cała aplikacja prezentuje się dobrze. Wszystkie kafle są dobrze widoczne i dobrze opisane. Opisy zakładek oraz button’ów dobrze oddają ich zawartość. Użytkownik wie czego się spodziewać klikając dany button. Cały design aplikacji jest dobrze przemyślany, schludny i estetyczny.

- *Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?*

**Propozycje zmian:**

1. Inny tryb kolorystyczny, aby można było wybrać (np. większy kontrast dla osób z wadami wzroku)
2. Pole “profil” jako zakładka na dolnym panelu
3. Inne możliwe języki do wyboru np. francuski, hiszpański


- *Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?*

Pierwszą różnicą jest poruszanie się po aplikacji, w testowaniu aplikacji webowej używa się touchpada lub myszki, a w przypadku aplikacji mobilnej dotykowego ekranu. Dodatkowo często w przypadku aplikacji mobilnej wymagane jest posiadanie konta użytkownika, a w aplikacji internetowej nie. Kolejną różnicą jest konieczność podłączenia do sieci internetowej - aplikacja internetowa wymaga bycia online, a mobilna może wyświetlać pewne elementy podczas trybu offline.


<h2>Subtask 4* - Testy aplikacji mobilnej i webowej.</h2>
Link: https://testerzy.atlassian.net/

<h1>Task 5</h1>
<h2>Subtask 1 - Krótki kurs podstaw SQL</h2>

Operatory/zapytania jakich się nauczyłam:

- Select * From X
- Select * From X Where 
- Insert
- Order by
- AND
- OR
- NOT
- LIKE
- IN
- BETWEEN

<h2>Subtask 2 - Konfiguracja środowiska i wgranie bazy danych</h2>

**Serwer:**

![image](https://user-images.githubusercontent.com/115873646/204394419-ce68fb8d-3f5d-4415-b819-5fa05d3c7106.png)

**Baza danych:**

![image](https://user-images.githubusercontent.com/115873646/204394744-047fa785-7871-467e-8ec6-87a542a6c8d0.png)

<h2>Subtask 3 - Kilka zadań na rozgrzewkę</h2>

*1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.*

**SELECT * FROM actors ORDER BY surname;**

![image](https://user-images.githubusercontent.com/115873646/204381244-a3333302-9353-45fc-9afd-f95a9710e60b.png)

*2. Wyświetl film, który powstał w 2019 roku.*

**SELECT * FROM movies WHERE year_of_production = 2019;**

![image](https://user-images.githubusercontent.com/115873646/204381596-d8e67840-30be-4152-a796-cd5d432163a8.png)

*3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem*

**SELECT * FROM movies WHERE year_of_production BETWEEN 1900 AND 1999;**

![image](https://user-images.githubusercontent.com/115873646/204382206-6d35c402-38b8-4491-9dc7-7abdb90f049b.png)

*4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$*

**SELECT title, price FROM movies WHERE price<7;**

![image](https://user-images.githubusercontent.com/115873646/204384516-7bd7e771-4943-44e4-8005-b4643def7397.png)

*5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.*

**SELECT * FROM actors WHERE actor_id>='4' AND actor_id<='7';**

![image](https://user-images.githubusercontent.com/115873646/204391846-037c57f1-f804-46d4-b175-602ee4c355b7.png)

*6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.*

**SELECT * FROM customers WHERE customer_id='2' OR customer_id='4' OR customer_id='6';**

![image](https://user-images.githubusercontent.com/115873646/204389669-b549ce47-d9e8-4cba-a272-80b4b48293b4.png)

*7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.*

**SELECT * FROM customers WHERE customer_id IN (1, 3, 5);**

![image](https://user-images.githubusercontent.com/115873646/204383139-2ee4cff5-0c7e-41d1-a850-2aed1717005b.png)

*8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.*

**SELECT * FROM actors WHERE name LIKE 'An%';**

![image](https://user-images.githubusercontent.com/115873646/204387293-39cc3ab6-856e-49ee-9217-5a8c62d21676.png)

*9. Wyświetl dane klienta, który nie ma podanego adresu email.*

**SELECT * FROM customers WHERE email IS NULL;**

![image](https://user-images.githubusercontent.com/115873646/204380961-82fb5ffb-6d90-4cc5-8be0-800aadd32733.png)

*10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.*

**SELECT * FROM movies WHERE price>9 AND movie_id>='2' AND movie_id<='8';**

![image](https://user-images.githubusercontent.com/115873646/204392609-a7856f1e-21ff-44c3-b6ae-79b916817603.png)


<h1>Task 6</h1>
<h2>Subtask 1 - Krótki kurs podstaw SQL</h2>

*11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈*

*12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.*

*13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: [pati@mail.com](mailto:pati@mail.com)*

*14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).*

*15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag*

*16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.*

*17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)*

**SELECT name FROM actors
UNION
SELECT name FROM customers
ORDER BY name;**

![image](https://user-images.githubusercontent.com/115873646/205969446-2f0de117-caa8-4f74-8f4d-ca5796ad746f.png)

*18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).*

*19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał*

*20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = [honia@mail.com](mailto:honia@mail.com) oraz pseudonym = Hoa*

**ALTER TABLE customers
ADD pseudonym varchar(255);
INSERT INTO customers (customer_id, name, surname, email, pseudonym)
VALUES ('7', 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa');**

![image](https://user-images.githubusercontent.com/115873646/205974677-7c07b8ca-dac7-4520-9c5f-96e814ffcdb2.png)


<h2>Subtask 2 - Test</h2>
Wynik: 14/15

<h2>Subtask 3 - Porfolio</h2>
Link: https://github.com/karolinafer/PORTFOLIO
