# Location-games-organiser

założenia projektu:

Każdy uczestnik biegu może załozyć konto, które:
-pozwala na utworzenie drużyny na daną impreze
-pozwala na dołączanie do drużyny innych uczestników jako członków (obserwatorów - bez możliwości edycji)
-pozwala sprawdzić rózne dane statystyczne (ilość biegów w których wzięło się udział, najlepsze miejsce itd.)

Drużyna (utworzone osobno na każdy event):
-po zeskaniowaniu kodu z punktu, uzyskać możliwość "wirtualnego" odwiedzenia punktu lub/i przesłania odpowiedzi na pytanie z danego pkt
-pod koniec biegu przesłania karty ekipy

Organizator musi:
-przygotować baze danych z punktami oraz kodami do danych punktów

Organizator może:
-zobaczyć o której jaka ekipa zeskanowała jaki punkt
-zobaczyć odpowiedzi na pytania każdej drużyny
-sprawdzić liste drużyn zgłoszonych na imprezę oraz dowolnie edytować


Działanie;
Po zeskanowaniu punktów, w sposób niewidoczny dla użytkownika wysyłane jest zapytanie do serwera, który zwraca dane potrzebne do "wirtualnego" odwiedzenia pktu, wszystkie zeskanowane pkty wypisuje w formie listy
