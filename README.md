# 🎲 Dobbelen

Drankspel met 2 dobbelstenen, gebaseerd op Mexen (met eigen regels). Werkt in de browser en is te installeren als app op je telefoon (PWA).

## Online zetten via GitHub Pages

1. Ga op GitHub naar **Settings → Pages** en kies bij **Source** voor **GitHub Actions**.
   (Voor een privé-repo heb je daarvoor een betaald GitHub-abonnement nodig; anders maak je de repo openbaar.)
2. Push naar de standaardbranch (of start de workflow **Deploy naar GitHub Pages** handmatig onder **Actions**).
3. Je spel staat dan op `https://<jouw-gebruikersnaam>.github.io/Dobbelen/`.

## Installeren op je telefoon

- **Android (Chrome):** open de link, tik op **📲 Installeer als app** of op het menu ⋮ → *Toevoegen aan startscherm*.
- **iPhone (Safari):** open de link, tik op Deel → *Zet op beginscherm*.

Na de eerste keer werkt het spel ook zonder internet.

## Lokaal testen

Open `index.html` in een browser. Voor de service worker (app-installatie) is een webserver nodig, bijvoorbeeld `python3 -m http.server` en dan `http://localhost:8000`.
