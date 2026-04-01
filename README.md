# Aromi di Vino

Sito web per **Aromi di Vino**, enoteca moderna a Fucecchio (FI). Sviluppato in HTML5, CSS3 e JavaScript vanilla — nessun framework, nessuna dipendenza da CMS.

## Struttura del progetto

```
aromi-di-vino/
├── css/
│   └── style.css          # Stili principali (mobile-first, CSS custom properties)
├── js/
│   └── main.js            # Logica: header sticky, hamburger menu, fade-in, smooth scroll
├── img/
│   ├── logo/              # Logo SVG e PNG
│   ├── icons/             # Icone social (Instagram, Facebook)
│   ├── bg-ambient.jpg     # Background sezione contatti
│   ├── bg-gray.jpg        # Background alternativo
│   ├── enoteca-e-degustazioni-a-fucecchio.jpg
│   ├── enoteca-fucecchio-aromi-di-vino.jpg
│   ├── foto-giacomo-carusi-enoteca-fucecchio.jpg
│   ├── onda.png           # Decorazione wave
│   └── riga-chiara.png    # Divisore hero
└── index.html             # Pagina unica (one-page)
```

## Tecnologie

- **HTML5** – markup semantico, ARIA, SEO on-page
- **CSS3** – Flexbox, Grid, custom properties, animazioni, media queries mobile-first
- **JavaScript (Vanilla)** – nessuna dipendenza esterna

## Sezioni

| Sezione | Descrizione |
|---|---|
| Hero | Immagine a schermo intero, titolo, indicatore di scroll |
| L'enoteca | Presentazione dell'enoteca con foto e testo |
| L'enologo | Bio di Giacomo Carusi con foto |
| Contattami | CTA per prenotare su WhatsApp |
| Footer | Indirizzo, orari, social |

## Avvio in locale

Basta aprire `index.html` nel browser, oppure avviare un server locale nella cartella del progetto:

```bash
# Python 3
python -m http.server 3000
```

## Breakpoint responsive

| Dispositivo | Breakpoint |
|---|---|
| Mobile | < 640px |
| Tablet | ≥ 640px |
| Desktop | ≥ 768px |
| Wide | ≥ 900px |