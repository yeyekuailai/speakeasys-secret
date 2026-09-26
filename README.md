# Speakeasy's Secret

An English-first, bilingual guide to New York City's hidden cocktail bars. It combines a playful illustrated borough map, independently verified venue details, official-menu links, and a searchable guide to 100 classic cocktails.

Live site: https://yeyekuailai.github.io/speakeasys-secret/

## Features

- Illustrated NYC map with mouse-wheel zoom and drag navigation
- Borough and price filters
- Venue addresses, selection criteria, and official menu links
- English and Chinese interface
- Searchable “100 Cocktails” guide with spirit filters and core ingredients
- Cinematic entrance animation

## Run locally

Serve the static site from the project root:

```bash
python3 -m http.server 4173 --directory dist
```

Then open `http://localhost:4173`.

## Structure

- `dist/index.html` — site layout, styles, and interactions
- `dist/assets/cocktails.js` — the 100-cocktail guide
- `dist/assets/entrance-frame-*.png` — entrance animation keyframes
- `dist/assets/gsap.min.js` — local animation runtime

Cocktail specs are concise reference builds; recipes and proportions vary by bar.
