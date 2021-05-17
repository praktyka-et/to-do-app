# Zalożenia projektu To-Do-App 

## Spis treści
1. Wymagania techniczne aplikacji
1. Struktura aplikacji
1. Kolorystyka aplikacji
1. Zalożenia funkcjonalne
     - dodawanie itemów do listy
     - oznaczenia elementów
     - usuwanie itemów z listy
     - limity 
1. Założenia niefunkcjonalne
     - Wyświetlanie itemów w formie listy
     - struktura aplikacji
     - przechowywanie danych
     - struktura danych
     - szczegóły 
     - Kolorystyka aplikacji
     - wymogi

## Wymagania techniczne aplikacji

1. Aplikacja powinna działać tak samo dobrze na wszystkich dotępnych przeglądarkach internetowych
1. Aplikacja powinna odczytywać dane z serwera przy każdym logowaniu się użytkownika
1. Aplikacja będzie wykonana w technologii node.js, HTML5, niereracylnej bazy danych MongoDB oraz arkusza styli CSS3.
1. Wykonawca dostarczy kod źródłowy apliakcji, który będzie umieszczony na repezytorium


## Struktura aplikacji
1. Struktura informacji prezentowanych na stronie powinna być zoruzmiała i spójna dla użytkownika
1. poszczególne sekcje aplikacji powinny być rozmieszczone intyuicyjnie i w sposób nieuttrudniający użytkownikowi korzystaia z niej
1. Komunikaty o błędach powinny sugerować ich rozwiązanie.
1. W odpowienich miejscach powinny znjadować się podpowiedzi lub podpisy danego elementu, tak aby nie utrudniało to korzystania z aplikacji użytkownikowi
1. Nawigacja po aplikacji powinna być intyuicyjna i przejrzysta dla użytkownika
1. Aplikacja powinna działać zarówno na urządzeniach mobilnych jak i komputerach, odpowiednio dopasowując się do rozdzielczości urządzenia z jakiego w danym momencie korzysta użytkownik
1. aplikacja powinna posiadać panel logowania, z możliwością zarejestrowania się jako nowi użytkownicy, lub zalogowania się na założone już wcześniej konto
1. Aplikacja będzie korzystać z fonta o nazwie "Lato"

## Kolorystyka aplikacji
1. Aplikacja powinna zapewniać wysoki kontrast między tekstem a tłem, by ułatwić użytkownikowi czytanie informacji
1. aplikacja będzie wykonana w schemacie blurple - jest to idelanie połączenie czerni z kolorem niebieskim, co pozwoli na zbytnie nie przemęczanie oczu użytkowniku podczas korzystania z apliakcji

## Założenia funckjonalne
1. Dodawanie Itemów do listy
     - Dodawanie zadań do listy To-Do odbywać się będzie po kliknięciu przycisku podpisanego (dodaj zadanie), po dodaniu zadania powinien on być widoczny na  liście użytkownika. 
     - Wraz z dodaniem elementu użytkownik powinien mieć możliwość podania konkretnej daty do jakiej dane zadanie ma zostać wykonane, data będzie widniała po prawej stronie dodanego elementu
1. Oznaczenia elementów
     - Podczas dodawania itemu do listy użytkownik powinien mieć możliwość dodania zadania z "priorytetowym" oznaczeniem, zadanie będzie wtedy widniało pod kolorem czerownym  
1. Usuwanie itemów z listy
     - Po dodaniu przez użytkownika zadania, powinien pojawić się obok niego przycisk (podpisany usuń) umożliwiający jego usunięcie   
     - Po dodaniu zadania przez użytkownika powinien pojawić się również button (podpisany "USUŃ WSZYSTKO") umożliwiający usunięcie całej listy
1. Limity
     - Aplikacja nie powinna ograniczać użytkownika poprzez ustaloną granicę maksymalnej ilości dodanych zadań. Jedyną blokadą jaką aplikacja powinna posiadać jest próba wpisania zadania o takiej samej treści jakie widnieje na liście, podczas takiej próby powinien pojawić się error informujący użytkownika o powodzie niepowodzenia dodania zadania.       

## Założenia niefunkcjonalne

1. Wyświetlanie Zadań w formie listy
     - Po wcześniejszym dodaniu zadania powinny się one wyświetlać się w formie imitującej liste      
1. przechowywanie danych
     -Dane użytkownika po zalogowaniu powinny zapisywać się w bazie danych
1. szczegóły 
     - Aplikacja po wpisaniu i dodaniu przez użytkownika zadania do listy, w ramach estetyki powinna wyczyścić polę do jakiego użytkownik wcześniej dodał zadanie 
     -Aplikacja będzie posiadać nagłówek o wielkości 50px, reszta tekstu powinna posiadać wielkość nie większą niż 20px. 
 1. Wymogi
     - Wymogiem korzystania z aplikacji będzie posiadanie przez użytkownika posiadanie zainstalowanej na urządzeniu przeglądarki internetowej
     - Wymogiem korzystania z aplikacji będzie posiadanie przez użytkownika stabilnego łącza internetowego