# Workshop_05
Warsztaty Spring MVC REST

<h3> Cel warsztatu </h3>
  Celem warsztatu jest napisanie funkcjonalności backendowej do katalogowania książek metodą REST.

W ramach warsztatu stworzymy API tożsame z tym które zostało udostępnione w ramach warsztatu poprzedniego (Javascript i Jquery).

Do stworzenia API wykorzystamy Spring MVC, dodatkową bibliotekę Jackson, oraz dodatkowe adnotacje.

Do ostatecznej weryfikacji poprawności naszego api wykorzystamy poprzedni frontendowy warsztat - zmieniając jedynie adres api, z którego ma ono korzystać.

Server powinien mieć zaimplementowane ścieżki dostępu podane w tabeli: 

GET	/books/	Zwraca listę wszystkich książek.<br>
POST	/books/	Tworzy nową książkę na podstawie danych przekazanych z formularza i zapisuje ją do bazy danych.<br>
GET	/books/{id}	Wyświetla informacje o książce o podanym id.<br>
PUT	/books/{id}	Zmienia informacje o książce o podanym id na nową.<br>
DELETE	/books/{id}	Usuwa książkę o podanym id z bazy danych.<br>
