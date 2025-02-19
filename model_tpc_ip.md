#**Porównanie modelu OSI i TPC/IP**
| Nazwa | Warstwy | Opis |
|-------|---------|------|
|OSI| 7 warstwa aplikacji|Umożliwia komunikację aplikacji użytkownika z siecią (np. HTTP, FTP, DNS).|
|| 6 warstwa prezentacji|Odpowiada za formatowanie danych (np. szyfrowanie, kompresja) oraz kodowanie informacji.
|| 5 warstwa sesji| Zarządza sesjami i synchronizuje wymianę danych (np. otwieranie, utrzymywanie, zamykanie sesji).
|| 4 warstwa transportu| Zapewnia niezawodną komunikację end-to-end (np. TCP, UDP).
|| 3 warstwa sieciowa| Odpowiada za routing i adresowanie (np. IP, routing, fragmentacja).
|| 2 warstwa łącza danych| Zarządza transmisją danych na poziomie połączenia między dwoma urządzeniami (np. Ethernet).
|| 1 warstwa fizyczna| Odpowiada za fizyczne połączenie urządzeń i transmisję bitów przez medium (np. kable, fale radiowe).
|TPC/IP| 4 warstwa aplikacji| Odpowiada za interakcję aplikacji z użytkownikiem oraz protokoły wyższego poziomu (np. HTTP, FTP, DNS).
|| 3 warstwa transportu|Zapewnia komunikację end-to-end, niezawodną transmisję danych (np. TCP, UDP).
||2 warstwa sieciowa|Zajmuje się adresowaniem, routingiem i przekazywaniem pakietów (np. IP, ICMP).
||1 warstwa dostępu do sieci| Odpowiada za komunikację z fizycznym medium, kontrolę dostępu do medium transmisyjnego (np. Ethernet).|

#**Najpopularniejsze protokoły TCP/IP**
|Nazwa|Opis|Zastosowanie|
|-----|----|---|
|TCP (Transmission Control Protocol)| Protokół transportowy zapewniający niezawodną komunikację między urządzeniami. TCP gwarantuje, że dane zostaną dostarczone w odpowiedniej kolejności i bez błędów. Używa mechanizmów takich jak potwierdzenia, retransmisje i kontrola przepływu.|Strony internetowe (HTTP/HTTPS), poczta elektroniczna (SMTP), transfer plików (FTP).|
|UDP (User Datagram Protocol)|Protokół transportowy, który jest bardziej lekki niż TCP, ponieważ nie zapewnia niezawodności (brak retransmisji ani potwierdzeń). UDP jest używany tam, gdzie szybkość jest ważniejsza niż gwarancja dostarczenia danych.|Streaming wideo/audio, gry online, transmisje na żywo, DNS.|
|IP (Internet Protocol)|Protokół warstwy sieciowej, który zajmuje się adresowaniem i trasowaniem pakietów pomiędzy różnymi sieciami. IP umożliwia komunikację w Internecie poprzez nadawanie każdemu urządzeniu unikalnego adresu IP.|Adresowanie urządzeń w sieci, trasowanie pakietów w Internecie.|
|HTTP (HyperText Transfer Protocol)|Protokół aplikacji, który jest podstawą wymiany informacji w Internecie. HTTP służy do przesyłania dokumentów HTML oraz innych zasobów webowych (obrazy, style, skrypty).|Przeglądanie stron internetowych, pobieranie danych z serwerów webowych.|
|HTTPS (HyperText Transfer Protocol Secure)|Szyfrowana wersja protokołu HTTP, która zapewnia bezpieczeństwo danych poprzez użycie SSL/TLS. HTTPS jest powszechnie stosowany w witrynach wymagających poufności (np. bankowość internetowa).|Bezpieczne przeglądanie stron internetowych, transakcje online.|