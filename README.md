## Opis
Projekt ten służy do wyświetlania losowych cytatów wraz z nazwiskami ich autorów. Używa Bootstrapa do stylizacji oraz API do pobierania cytatów.

## Używane serwisy

### Bootstrap
- **URL**: [Bootstrap](https://getbootstrap.com/)
- **Zastosowanie**: Używany do stylizacji interfejsu użytkownika.
- **Wersja**: 4.3.1

### API Quotes
- **URL**: [RapidAPI - Random Quotes](https://rapidapi.com/)
- **Zastosowanie**: Używane do pobierania losowych cytatów.
- **Metoda**: GET
- **Endpoint**: `/quotes/random/?language_code=en`

## Używane metody

### Fetch API
- **Zastosowanie**: Do wykonywania zapytań do API Quotes i pobierania danych.
- **Wyniki działania**: 
  - Pobiera losowy cytat i jego autora.
  - Wyświetla te informacje w interfejsie użytkownika.

### HTML/CSS
- **Zastosowanie**: Do tworzenia i stylizacji struktury strony.

## Jak uruchomić
1. Pobierz pliki projektu.
2. Otwórz `index.html` w przeglądarce.

## Uwagi
- Klucz API (`MY_API_KEY`) jest wymagany do korzystania z API Quotes i musi być przechowywany w osobnym pliku `config.js`.

## Przykładowy wynik działania
- Cytat: "To be or not to be, that is the question."
- Autor: William Shakespeare
- (Wszystkie cytaty będąw języku angielskim)
