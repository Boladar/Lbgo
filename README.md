# Location-games-organiser

założenia projektu:

1. Każdy uczestnik biegu może załozyć konto, które:
1. pozwala na utworzenie drużyny na daną impreze
2. pozwala na dołączanie do drużyny innych uczestników jako członków (obserwatorów - bez możliwości edycji)
3. pozwala sprawdzić rózne dane statystyczne (ilość biegów w których wzięło się udział, najlepsze miejsce itd.)

2. Drużyna (utworzone osobno na każdy event):
1. po zeskaniowaniu kodu z punktu, uzyskać możliwość "wirtualnego" odwiedzenia punktu lub/i przesłania odpowiedzi na pytanie z danego pkt
2. pod koniec biegu przesłania karty ekipy

3. Organizator musi:
1. przygotować baze danych z punktami oraz kodami do danych punktów

4. Organizator może:
1. zobaczyć o której jaka ekipa zeskanowała jaki punkt
2. zobaczyć odpowiedzi na pytania każdej drużyny
3. sprawdzić liste drużyn zgłoszonych na imprezę oraz dowolnie edytować


5. Działanie;
1. Po zeskanowaniu punktów, w sposób niewidoczny dla użytkownika wysyłane jest zapytanie do serwera, który zwraca dane potrzebne do "wirtualnego" odwiedzenia pktu, wszystkie zeskanowane pkty wypisuje w formie listy
