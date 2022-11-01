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
