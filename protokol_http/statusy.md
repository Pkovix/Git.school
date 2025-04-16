1XX – Informacyjne
Zakres: 100–199

Znaczenie: Żądanie zostało odebrane i przetwarzane, ale odpowiedź jeszcze nie jest kompletna. Używane rzadko.

Przykłady:

100 Continue – Serwer otrzymał początkową część żądania, klient może kontynuować.

101 Switching Protocols – Serwer zgadza się na zmianę protokołu (np. z HTTP na WebSocket).

2XX – Sukces
Zakres: 200–299

Znaczenie: Żądanie zostało prawidłowo przetworzone.

Przykłady:

200 OK – Standardowa odpowiedź sukcesu.

201 Created – Zasób został utworzony (np. po dodaniu rekordu przez API).

204 No Content – Żądanie zakończone sukcesem, ale brak danych w odpowiedzi.

3XX – Przekierowania
Zakres: 300–399

Znaczenie: Klient musi podjąć dodatkowe działania (np. zostać przekierowany).

Przykłady:

301 Moved Permanently – Trwałe przekierowanie na inny URL.

302 Found – Tymczasowe przekierowanie.

304 Not Modified – Zasób nie został zmodyfikowany, można użyć wersji z cache.

4XX – Błędy po stronie klienta
Zakres: 400–499

Znaczenie: Błąd w żądaniu klienta, np. niepoprawna składnia lub brak uprawnień.

Przykłady:

400 Bad Request – Niepoprawne żądanie (np. błędne dane wejściowe).

401 Unauthorized – Wymagana autoryzacja.

403 Forbidden – Zakaz dostępu mimo poprawnej autoryzacji.

404 Not Found – Żądany zasób nie istnieje.

5XX – Błędy po stronie serwera
Zakres: 500–599

Znaczenie: Serwer napotkał błąd i nie mógł przetworzyć żądania.

Przykłady:

500 Internal Server Error – Ogólny błąd serwera.

502 Bad Gateway – Serwer pośredniczący otrzymał błędną odpowiedź.

503 Service Unavailable – Serwer jest przeciążony lub niedostępny.