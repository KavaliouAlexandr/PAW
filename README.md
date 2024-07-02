# Lingua Front-End Presentation
This project describes Polish Lingua app. Polish Lingua is the application which gives an opportunity to learn Polish language in levels from A1 to C1. Each level has descriped tasks, multiple choice, single choice and tests. After fihishing the test, user gets a result and starts another level of learning language. Implementation described in this work consists of app appearence, sprints, tests, structure, which makes it easier to read the code correctly.

# Technologies
Angular
TypeScript
MongoDB
HTML
SCSS
GIT

4.2.	Prezentacja Front-Endu
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/af6e10ec-1d08-4939-a56e-a643752ce8a4)

Rysunek 9 Strona początkowa
4.2.1.	Strona początkowa
Strona początkowa posiada informację o aplikacji, możliwość zalogowania oraz stworzenia konta. To jest główna strona aplikacji, która prezentuje się jako projekt reprezentowany przez poziomy oraz zadania do zrealizowania. Po przechodzeniu po stronie użytkownik może stworzyć konto lub zalogować się. 
Strona początkowa jest istotnym elementem aplikacji, prezentuje ona podstawowy wygląd aplikacji. Przez wygląd strony początkowej użytkownik zauważa poważność deweloperów oraz właścicieli oraz decyduje czy będzie korzystał z aplikacji. Z tego powodu na realizacje strony początkowej zwraca się szczególną uwagę. 
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/e91b3f92-33dc-49cc-aae1-76a04d0c989a)
Rysunek 10 Strona logowania
4.2.2.	Strona logowania
Strona logowania posiada formularz zalogowania przy użyciu podanego przy rejestracji loginu oraz hasła. Także jest możliwość przejścia do rejestracji lub zmiany hasła. 
Na niniejszej stronie był wykorzystany prosty do interpretacji przez użytkownika responsywny UI w szarym kolorze. Podobne łatwe rozumienie strony pozwala użytkownikom każdego wieku na korzystanie z aplikacji.
![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/3c062af3-6392-4ae3-b2f3-a478c40a8f94)
Rysunek 11 Strona rejestracji
4.2.3.	Strona rejestracji 
Strona rejestracji zawiera formularz stworzenia konta nowego użytkownika za pomocą login, hasła oraz nazwy użytkownika. Również zawiera formularz do zmiany hasła. 
Przy rejestrowaniu użytkownik stwarza swój login i hasło do zalogowania oraz wprowadza swoje imię, za pomocą którego aplikacja będzie zwracać do użytkownika w ciągu nauki. Imię oraz wszystkie dane będą wyświetlane na stronie profilu użytkownika. 
W przypadku posiadania konta, formularz nie pozwoli na ponowną rejestracji oraz zaproponuje zalogowanie do swojego istniejącego konta lub zmianę hasła. 
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/45105f65-1e1a-4a26-a85d-c65f80d4836c)
Rysunek 12 Błędne dane logowania
4.2.4.	Strony logowania/rejestracji 
Podane strony posiadają walidację w przypadku wpisania niepoprawnych danych aplikacja nie pozwoli na rejestrację/logowanie. W takiej sytuacji strona proponuje zmianie hasła przyciskiem „nie pamiętasz hasła” lub stworzenie konta. Po tym jak użytkownik klika na stworzenie konta ze strony logowania automatycznie zmienia się na stronę rejestracji. 
![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/491f0e1e-63f4-4e82-9213-a7df39457ec7)
Rysunek 13 Strona Wszystkie poziomy
4.2.5.	Strona Poziomy
Na stronie znajdują się aktualne poziomy nauki języka Polskiego dla użytkowników. Każdy poziom zawiera przycisk do rozpoczęcia nauki oraz szczegóły z opisem każdego z poziomów. W szczegółach każdego z poziomów jest opisane jaka wiedza jest potrzebna do wykonywania zadań oraz testów. Dla nowych użytkowników zaleca się wybranie podstawowego poziomu A1.
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/e21329c1-edb6-4354-9c2a-b695b5f7df14)
Rysunek 14 Strona Logowanie-Admin
4.2.6.	Dostęp administratora
Aplikacja posiada dostęp administratora, który pozwala na edytowanie poziomów, błędów tematów dydaktycznych oraz testów. Możliwości niniejszego dostępu są ograniczone w celach bezpieczeństwa. 
Aplikacja jest kontrolowana przez Administratora, którego poziom dostępu pozwala na edycję poziomów, dodawanie treści, dodawanie zadań i kontrolowanie testów.
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/2bb1a615-deee-4bb5-ac48-8df11877b3a7)
Rysunek 15 Strona Zadania
4.2.7.	Strona Zadania/Test
Każdy poziom posiada przypisane do niego zadania z tematami do nauki oraz testy. Ilość zadań oraz testów planuje się być dalej rozszerzana za pomocą dodawania danych do bazy. Każdy poziom posiada 5 lub więcej zadań oraz testy. 
Na każdej stronie na dole są podane dane firmowe oraz kontakt do zespołu w przypadku błędów, pytań od użytkowników oraz nieprawidłowych informacji w tematach dydaktycznych. Z każdej strony jest możliwość powrotu do strony poziomów. Poziomy nie są ograniczone dostępem, ponieważ aplikacja musi być bezpłatna i dostępna dla wszystkich użytkowników. 
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/45cf414a-6340-4ee0-974c-2b7c7e167ba2)
Rysunek 16 Zadanie 1
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/760767f6-37e0-4a9f-b98c-ef8c664d18a2)
Rysunek 17 Zadanie 2
 ![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/2fc602bd-0916-469f-a12c-3f4a3088c2d6)
Rysunek 18 Zadanie 3
4.2.8.	Strona Zadanie
Aplikacja posiada 3 typy zadań. Zadania wielokrotnego wyboru, prawda/nieprawda oraz zadania z wpisywaniem odpowiedzi. Zadania z wpisywaniem odpowiedzi pozwalają na praktyczne wykorzystanie swojego słownictwa. Zadania z prawidłowym składaniem zdania pozwalają na praktykę ortografii. wykorzystaniem zdobytej wiedzy i sprawdzenia swoich umiejętności. 
Każde zadanie w zrozumiały sposób opisuje co jest potrzebne od użytkownika oraz dzięki prostemu UI użytkownik łatwo interpretuję informację.
•	Zadanie 1 (Rys 17) reprezentuje sobą zadanie z wpisywaniem odpowiedzi (tłumaczenie zdania na język polski) sprawdza się ogólny poziom wiedzy użytkownika. Także jest możliwość sprawdzenia wpisanego tekstu lub pominięcie ćwiczenia i jego powtórzenie później.
•	Zadanie 2 (Rys 18) reprezentuje sobą z składaniem zdania z już podanych słów, które losowo aplikacja pobiera z bazy danych. Użytkownik ma możliwość odświeżyć podane słowa w tym przypadku zdanie oraz słowa się zmienią. Przycisk sprawdź wyświetla komunikat który wskazuje wynik wykonania podanego zadania. W przypadku prawidłowej odpowiedzi wyświetla się komunikat po którym użytkownik przechodzi do nowego zadania.
•	Zadanie 3 (Rys 19) reprezentuje zadanie z wyborem odpowiedzi prawda/nieprawda po wysłuchaniu tekstu użytkownik musi odpowiedzieć na pytanie dotyczące nagrania. Po wyborze odpowiedzi użytkownik przyciskiem ich sprawdza. 
![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/e1714493-cb20-4df8-bc5e-869630eb95a8)
Rysunek 19 Strona Test
4.2.9.	Strona Test
Test składa się z 10 zadań, podobnych to zadań, które były wyświetlone wcześniej przed zakończeniem wybranego poziomu. W przyszłości planuje się zwiększenie ilości materiałów do nauki, zadań oraz testów. Przed testem użytkownik musi skończyć wybrany poziom. 
Po zakończeniu testu jest wyświetlony wynik oraz jest możliwość powtórzenia lub powrotu na stronę z zadaniami. Wynik jest wyświetlany jako koło, które wypełnia się zgodnie z wynikiem zakończonego testu. W przypadku wyniku mniej niż 50% aplikacja proponuje powtórzyć poziom. 
Test stanowi ogólny wynik ukończonego poziomu, daje możliwość sprawdzenia swoich wiedzy przez użytkownika. 
![image](https://github.com/KavaliouAlexandr/Lingua/assets/80467603/c4849875-0442-41ce-906d-92327539875a)
Rysunek 20 Strona Profil użytkownika
4.2.10.	Profil użytkownika 
Niniejszą stroną jest profil użytkownika (Rys 21). Posiada dane aktywnego użytkownika, poziom przepisany do niego oraz możliwość zmiany hasła za pomocą pytania pomocniczego. 
Profil użytkownika posiada nawigację, przez którą można wejść na stronę główną, poziomy, profil użytkownika oraz wylogować się. Wylogowanie wyświetli stronę początkową dla ponownego zalogowania przez innego użytkownika.
W przyszłości podana strona będzie rozwijana dodaniem dodatkowych funkcjonalności jak zmiana języka nauczania, wybór poziomu nauczania oraz dodanie zdjęcia przez użytkownika. 

