Nagłówki żądania (Request Headers)
Te nagłówki są wysyłane przez klienta (np. przeglądarkę) do serwera, żeby określić, co chce dostać i w jakiej formie:

Host – określa, do jakiego serwera kierowane jest żądanie.

Przykład: Host: www.example.com
Dzięki temu serwer wie, którą stronę obsłużyć (ważne dla serwerów obsługujących wiele stron).
User-Agent – informuje serwer, jaką przeglądarkę i system operacyjny używa klient.

Przykład: User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64)
Serwery mogą dostosować treść do urządzenia (np. mobilnego).
Accept – mówi serwerowi, jaki typ treści klient jest w stanie zaakceptować.

Przykład: Accept: text/html,application/json
Dzięki temu serwer może wysłać treść w odpowiednim formacie (np. HTML lub JSON).

Nagłówki odpowiedzi (Response Headers)
Serwer zwraca te nagłówki, żeby poinformować klienta, co wysłał i jak to przetworzyć:

Content-Type – określa typ zwróconej treści.

Przykład: Content-Type: application/json
Dzięki temu przeglądarka wie, jak wyświetlić dane (np. stronę HTML czy obraz).
Content-Length – mówi, jak długa jest treść odpowiedzi w bajtach.

Przykład: Content-Length: 2048
To pomaga klientowi określić, kiedy cała odpowiedź została odebrana.
Cache-Control – steruje, czy i jak długo odpowiedź może być przechowywana w pamięci podręcznej.

Przykład: Cache-Control: no-cache, must-revalidate
no-cache mówi, żeby zawsze pobrać nową wersję, a must-revalidate wymusza odświeżenie po wygaśnięciu.
