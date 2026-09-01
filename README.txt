PLAN LEKCJI 1B – WERSJA NA iPHONE

1. Umieść cały folder na hostingu WWW obsługującym HTTPS.
   Najprościej: GitHub Pages, Netlify, Vercel albo własny hosting.
   Google Drive nie jest dobrym hostingiem dla PWA.

2. Otwórz adres strony w Safari na iPhonie.

3. Stuknij „＋ Dodaj do ekranu głównego” w samej stronie, aby zobaczyć instrukcję.
   Następnie w Safari: Udostępnij → Dodaj do ekranu początkowego → Dodaj.

4. Ikona „Plan 1B” pojawi się na ekranie i będzie uruchamiała stronę w trybie
   przypominającym aplikację.

WAŻNE:
iOS/Safari ze względów bezpieczeństwa nie pozwala stronie WWW samodzielnie
wykonać kliknięcia „Dodaj do ekranu początkowego”. Dlatego tego ostatniego
kroku nie da się w pełni zakodować. Powyższy przycisk prowadzi użytkownika
przez wymagane działanie.

Pliki:
- index.html – aplikacja
- manifest.webmanifest – konfiguracja PWA
- sw.js – cache/offline
- icons/ – ikony aplikacji
