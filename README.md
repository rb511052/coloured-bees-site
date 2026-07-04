# Coloured Bees Consulting — Landing Site

A single-page static landing site for Coloured Bees Consulting GmbH.
No build step, no dependencies — just `index.html` and the brand assets.

## Structure

```
coloured-bees-site/
├── index.html        # the whole page (HTML + inline CSS)
└── assets/           # brand SVGs (logo, mark, bee swarm, patterns)
```

## Preview locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on **GitHub Pages** from the `main` branch. Any push to `main`
publishes automatically.

## Editing

All page copy lives in `index.html`. Brand colors, fonts, and spacing
are CSS variables in the `<style>` block near the top.
