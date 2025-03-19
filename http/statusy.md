🔵 1xx – Informacyjne (Informational)
Statusy z tej grupy oznaczają, że połączenie jest na dobrej drodze, ale jeszcze nie zakończono całej komunikacji. Klient powinien czekać na dalsze instrukcje.

100 Continue – serwer otrzymał część żądania i klient może kontynuować wysyłanie reszty.
101 Switching Protocols – serwer zgadza się na zmianę protokołu (np. z HTTP na WebSocket).
✅ 2xx – Sukces (Success)
Ta grupa oznacza, że żądanie zostało poprawnie przetworzone i zakończone sukcesem.

200 OK – wszystko poszło dobrze, treść jest zwracana (najczęstszy status).
201 Created – serwer utworzył nowy zasób, np. po wysłaniu formularza.
204 No Content – żądanie było poprawne, ale nie ma żadnej treści do zwrócenia (np. po usunięciu czegoś).
🔀 3xx – Przekierowania (Redirection)
Te statusy informują, że klient powinien spróbować pod innym adresem URL.

301 Moved Permanently – zasób został przeniesiony na stałe pod inny adres.
302 Found – zasób tymczasowo znajduje się pod innym adresem.
304 Not Modified – klient ma już aktualną wersję zasobu i nie musi go pobierać ponownie (przydatne przy cache).
🛑 4xx – Błędy po stronie klienta (Client Error)
Te statusy oznaczają, że problem leży po stronie klienta — żądanie jest niepoprawne lub nieautoryzowane.

400 Bad Request – żądanie jest źle sformułowane (np. zły format danych).
401 Unauthorized – brak autoryzacji, trzeba podać dane logowania.
403 Forbidden – serwer odmawia dostępu, mimo że żądanie jest poprawne.
404 Not Found – zasób nie został znaleziony (najbardziej znany status!).
🔥 5xx – Błędy po stronie serwera (Server Error)
Oznaczają, że coś poszło nie tak po stronie serwera, mimo poprawnego żądania od klienta.

500 Internal Server Error – ogólny błąd serwera (coś poszło nie tak, ale nie wiadomo co).
502 Bad Gateway – serwer pośredniczący (proxy) otrzymał złą odpowiedź od innego serwera.
503 Service Unavailable – serwer jest chwilowo niedostępny (np. przeciążenie lub konserwacja).
