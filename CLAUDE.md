# Emilio Lodigiani - Sito Personale

## Panoramica
Sito personale statico di Emilio Lodigiani. Landing page con sezioni: Hero, Tunca (agenzia ecommerce), Strategia eCommerce (corsi/podcast/youtube), Podere Montevalle (agriturismo), Footer con contatti e social.

## Stack Tecnico
- HTML statico + Tailwind CSS (CDN)
- Font: Archivo Black (display) + JetBrains Mono (body) via Google Fonts
- Nessun framework JS, nessun build system per il sito
- Puppeteer per screenshot di confronto (`screenshot.mjs`)

## Struttura File
- `index.html` - Pagina principale (unica pagina)
- `style.css` - Stili custom residui (pseudo-elementi, animazioni SVG)
- `images/` - Immagini del sito
- `screenshot.mjs` - Script per screenshot locale vs originale
- `old-site/` - Vecchio sito per riferimento

## Convenzioni di Stile
- Lingua del codice: inglese per classi e variabili, italiano per contenuti
- Design: bianco e nero, minimal, tipografia bold
- Colori principali: `#1a1a1a` (nero), `#fff` (bianco), `#555` (grigio)
- Mobile-first con breakpoint a 768px e 1024px
- Tailwind per la maggior parte degli stili, CSS custom solo per effetti non ottenibili con utility classes (pseudo-elementi decorativi, animazioni SVG wave)

## Comandi Utili
- `node screenshot.mjs` - Genera screenshot di confronto locale vs sito live

## Note
- Il sito originale e' su https://emiliolodigiani.it
- Link esterni: tunca.it, strategiaecommerce.com, montevalle.it, podcast Apple, canale YouTube
- Nessun git repository configurato al momento
