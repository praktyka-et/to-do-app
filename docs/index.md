# Zalożenia



## Założenia funckjonalne
1. Dodawanie Itemów do listy
     - Będzie one wykonywane po kliknięciu przycisku na stronie, każde poszczególne zadanie będzie wpisane do listy która znajduje się pod przyciskiem. Itemy te będą zapisywać się w liście ul> jako elementy li
     - Wraz z dodaniem elemntu powinniśmy mieć również możliwość ustalenia daty(terminu) do jakiego musi zostać wykonany, który będzie później widniał obok elementu na liście
1. Usuwanie itemów z listy
     - Po tym jak już dodamy swoje pierwsze zadanie, obok zadania pojawi sie przycisk umożliwiający usunięcie poszczególnego zadania,  
     - Po dodaniu pierwszego zadania w aplikacji powstanie przycisk umożliwiający wyczysczenie całej naszej listy, button umożliwijący zrobienie tego pojawi się nad naszą To-Do-Listą 
     - po dodaniu jednego (lub więcej) zadania, pojawi się pole, będzie je można zaznaczyć, po zaznaceniu itemu pojawi się przycisk umożliwiający usunięcie zaznaczonych itemów 
1. Limity
     - Aplikacja nie powinna posiadać limitów co do ilości zadań jakie będzie można dodać do naszej To-Do-Listy, jedyne jej ograniczenie(blokade) będzie stanowić próba wpisania zadania o takiej samej nazwie jakie widnieje już na naszej liście.       

## Założenia niefunkcjonalne

1. Wyświetlanie itemó w formie listy
     - Zadania(itemy), jakie dodamy za pomocą przycisku, będą się wyświetlać w formie imitującej liste, będą one wypunktowane(bądź ponumerowane)
1. struktura aplikacji   
     - Aplikacja będzie zbudowana tak by była responsywna(dopasowana zarówno na tablety i telefony), za backend strony będzie odpowiadał node.js a frontend będzie napisany za pomocą frameworku react 
     - aplikacja powinna nam przywitać panelem logowania, gdzie będziemy mogli zarejestrować się jako nowi użytkownicy, lub też zalogować jeżeli nasze konto już istnieje
1. przechowywanie danych
     -Dane po stronie frontu będą zapisywane w formie wcześniej wspomnianiej listy, będą one widoczne w podglądzie strony
     -Wszystkie dane po stronie BackEndu będą przechowywane w nierelacyjnej bazie danych o nazwie MongoDB  
1. struktura danych
     - Dane będą zapisywane w poszczególnych tabelach bazy danych o odpowiendich nazwach, każda poszczególna informacja taka jak np: nazwa użytkownika, będzie widniała w pojedynczym rekordzie w bazie
1. szczegóły 
     - Aplikacja w polu inputu po wpisaniu zadania które chcemy dodać do listy powinna wykasować informacje z inputa dla większego komfortu korzystania z aplikacji, aplikacja oczywiście powinna nie odświeżać na nowo okna przeglądarki za każdym razem jak dodamy zadanie do listy  
