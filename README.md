# Faam Document Generator

## Structuur
```
static/
├── index.html        ← de app
├── layout.json       ← veldposities (pas dit aan via admin modus)
├── images/
│   ├── cover.jpg     ← pagina 1 achtergrond
│   ├── page2.jpg     ← pagina 2 achtergrond
│   └── page3.jpg     ← pagina 3 achtergrond
└── fonts/
    └── Lufga-*.otf   ← Lufga font bestanden
vercel.json           ← Vercel routing naar static/
```

## Veldposities aanpassen (admin)
1. Open de app
2. Klik op **⚙ Velden plaatsen** rechtsboven
3. Sleep velden naar de juiste positie
4. Klik **↓ Exporteer layout.json**
5. Vervang `static/layout.json` in GitHub → Vercel herdeployt automatisch

## Afbeeldingen vervangen
Vervang de bestanden in `static/images/` — zelfde bestandsnamen aanhouden.
