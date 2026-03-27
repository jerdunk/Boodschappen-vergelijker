# Supermarkt Prijsvergelijker

Een Nederlandse supermarkt prijsvergelijker gebouwd met pure HTML, CSS en JavaScript. Vergelijk prijzen van je boodschappenlijst bij verschillende supermarkten en vind waar je het goedkoopst uit bent.

![Screenshot](screenshot.png)

## Features

- 🛒 **Boodschappenlijst invoer** - Typ je producten, één per regel
- 💰 **Prijsvergelijking** - Vergelijk prijzen bij 12+ supermarkten
- 🏆 **Goedkoopste eerst** - Supermarkten gesorteerd op totaalprijs
- 💾 **Automatisch opslaan** - Je lijst blijft bewaard (localStorage)
- 📱 **Responsive design** - Werkt op desktop en mobiel
- 🔒 **Privacy-first** - Alles draait in je browser

## Ondersteunde Supermarkten

- Albert Heijn
- Jumbo
- ALDI
- Coop
- Dirk
- Hoogvliet
- Jan Linders
- Picnic
- Plus
- SPAR
- Vomar
- DekaMarkt

## Installatie

### Optie 1: Direct gebruiken
Open `index.html` in je browser. Dat is alles!

### Optie 2: GitHub Pages
1. Fork deze repository
2. Ga naar Settings > Pages
3. Selecteer "main" branch
4. Je site is live op `https://[username].github.io/[repo-name]/`

### Optie 3: Lokale webserver
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

## Gebruik

1. Voer je boodschappen in, één product per regel
2. Klik op "Vergelijk prijzen"
3. Bekijk welke supermarkt het goedkoopst is

### Tips voor betere resultaten

- Wees specifiek: `halfvolle melk 1,5 liter` werkt beter dan `melk`
- Voeg hoeveelheden toe: `6 eieren`, `1 kg bananen`
- Merknamen helpen: `Calvé pindakaas` i.p.v. alleen `pindakaas`

## Technische Details

### Stack
- Pure HTML5, CSS3, JavaScript (ES6+)
- Geen build tools nodig
- Geen frameworks

### Dependencies
- [checkjebon-js](https://github.com/supermarkt/checkjebon-js) - Prijsdata en zoekalgoritme
- [Font Awesome](https://fontawesome.com/) - Iconen (via CDN)

### Data
Prijsdata wordt geleverd door [Checkjebon.nl](https://www.checkjebon.nl/) en wordt dagelijks bijgewerkt. De data wordt direct vanuit de checkjebon-js library geladen.

## Licentie

MIT License - Vrij te gebruiken en aan te passen.

## Credits

- Prijsdata: [Checkjebon.nl](https://www.checkjebon.nl/)
- checkjebon-js library: [supermarkt/checkjebon-js](https://github.com/supermarkt/checkjebon-js)

## Zelf uitbreiden?

Enkele ideeën:
- Kassabon scanner (met Tesseract.js)
- Boodschappenlijst delen via URL
- Favoriete supermarkt instellen
- Prijsgeschiedenis bijhouden
- PWA maken voor offline gebruik
