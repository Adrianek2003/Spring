Jest to prosta aplikacja działająca zgodnie z modelem MVC. Wykorzystujemy tu jav'owy framework Spring Boot oraz szblony stron internetowych Thymeleaf.

Na samą aplikację składają się w zasadzie dwa elementy:
    Kontroler (HelloController), zwierający w sobie dwa tzw. endpoint'y:
        Endpoint "/" jeżeli użyjemy RestController'a zwraca nam szablon dokumentu html z tekstem "Hello Vistula, from my first spring controller".

        Endpoint "/greeting" przyjmuje parametr name (domyślnie "World") w postci przesyłu metdoą GET (ja bym wolał użyć POST) i przekazuje go do widoku,gdzie ten zostanie wklejony w tekst wyświwtlany w paragrafie.

    Widok:
        Plik HTML greeting.html wyświetla powitanie w zależności od wartości zadanej dla parametru name, a także dodatkowy tekst w postaci
        Lorem Ipsum oraz oraz obrazek.

Osobiście już raz spotkałem się z wykorzystaniem wzorca tworzenia aplikacji internetowchy zgodnie z MVC. Było to przy pisaniu aplikacji z wykorzystaniem framework'a PHP jakim był Laravel.
W sumie sama koncepcja mocno się nie różni, jednak java wydaje się być lepszym wyborem przez wzgląd na leciwość języka PHP.