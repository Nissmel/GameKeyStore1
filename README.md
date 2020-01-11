# GameKeyStore
Celem projektu jest stworzenie sklepu internetowego na w frameworku Spring. Sprzedaż kluczy do gier, płatność Przelewy24, wysyłka elektroniczna email. W repozytorium został umieszczony projekt TacoCloud, który będzie dobrym początkiem dla całości projektu. Aktualnie znajduję się tam strona dla wyboru rodzaju oraz dodatków do Taco xD. Jednak jest już gotowa baza danych Hibernate, oraz połączenia do obiektów. Wystarczy przeskalować to co mamy już obecnie, dodać gry i tą nieszczęsną płatność. *Gut lak.* :+1:

#### Repozytorium możecie śmiało edytować, dodawać oraz zmieniać. Co wam przychodzi do głowy to dopisujcie do listy TODO, jesli coś ukończymy to wystarczy dodać 2x tylda przed i po elemencie - znaczek Shift+przycisk przed '1' ~~przykład~~
**formatowanie tego pliku [instrukja](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)**

## TODO
1. nazwa sklepu

2. baza  danych:
   - *GamesAlavaible (ID_Game, Id_Key, GameName)*
   - *GamesSold (ID_Game, Id_Key, GameName,Date)*
   - *Clients (ID_Client, Email, Name, SurrName)*
   - *Transaction (ID_Game, ID_Client, ID_Key, Date, IsPaymentValid)* 
   
3.instalacja [Przelewy24](https://www.przelewy24.pl/dla-firm/instalacja)
Wersja w wykonaniau Kanclerza [tutaj](https://github.com/jkanclerz/car-rental-spring/tree/master/src/main/java/pl/jkan/przelewy24
)






