#EVENTEES

AUTORZY
  Sebastian Piaścik
  Sonia Stenzel

OPIS
  Aplikacja internetowa do obsługi wydarzeń sportowych.
  System umożliwia zrzeszanie się ludzi w celu wspólnego uprawiania wybranej dyscypliny sportowej.

WYMAGANIA
  * baza danych mysql
  * php >=7.1.3
  * composer
  * php artisan
  * npm

URUCHIOMIENIE

  * W FOLDERZE /API
    $ composer install
    $ php artisan migrate --seed
    $ php -S localhost:8000 -t public

    w osobnej konsoli:
    $ php artisan queue:listen

  * W FOLDERZE /APP
    $ npm install
    $ npm start
