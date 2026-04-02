# B&S Transport GmbH — Website

Professionelle, zweisprachige Firmenwebsite für die B&S Transport GmbH.

## Struktur

```
bs-transport/
├── index.html          ← Deutsche Startseite
├── impressum.html      ← Impressum (TODO)
├── datenschutz.html    ← Datenschutz (TODO)
├── css/
│   └── style.css       ← Globale Styles
├── js/
│   └── main.js         ← Navigation, Scroll, Sprache
├── img/
│   └── favicon.svg     ← Favicon
└── en/
    └── index.html      ← Englische Startseite
```

## Tech-Stack

- **Reines HTML / CSS / Vanilla JS** — kein Framework, kein Build-Prozess
- **Fonts**: Playfair Display (Überschriften) + DM Sans (Body) via Google Fonts
- **Responsive**: Mobile-first, Breakpoints bei 600px und 960px
- **SEO**: Meta-Tags, Open Graph, semantisches HTML

## Lokale Vorschau

```bash
# Mit Python
python3 -m http.server 8000

# Oder mit Node.js
npx serve .
```

Dann: http://localhost:8000

## Deployment

Die Dateien sind statisches HTML und können auf **jedem Hosting** deployed werden:
- Upload per FTP/SFTP auf den Kundenserver
- Oder via GitHub Pages, Netlify, Vercel, etc.

## TODO

- [ ] Kontaktformular (Formspree / Web3Forms)
- [ ] Impressum & Datenschutz-Seiten
- [ ] Bilder/Fotos (Fuhrpark, Team, Standort)
- [ ] Logo als SVG (sobald finales Design steht)
- [ ] Domain einrichten & HTTPS aktivieren
