# Harunova farma 3D

Prva igriva web-verzija prototipa u Three.js. Namijenjena je GitHub Pages hostingu.

## Objavljivanje na GitHub Pages
1. Napravi repozitorij `harunova-farma`.
2. Uploadaj `index.html`, `styles.css` i folder `src` u korijen repozitorija.
3. Otvori **Settings → Pages**.
4. Izaberi `Deploy from a branch`, branch `main`, folder `/ (root)`, pa sačuvaj.
5. Otvori GitHub Pages link. Potrebna je internet veza jer se Three.js učitava preko CDN-a.

## Kontrole
- Računar: WASD ili strelice za kretanje/vožnju; E ulazak/izlazak iz traktora; F interakcija.
- Telefon: dodirni parcelu da je odabereš; u traktoru koristi virtuelne kontrole.
- Paneli omogućavaju upravljanje usjevima, životinjama, prodajom, inventarom i kalendarom.

## Napomene
Ovo je početni funkcionalni prototip. Geometrija objekata je privremena, zvučni fajlovi još nisu dodani, a prodaja je osnovna i još ne provjerava fizičku blizinu prodajnog mjesta. Čuvanje koristi `localStorage` i nije sinhronizovano između uređaja. Otvaraj preko GitHub Pages, ne direktno kao `file://`.
