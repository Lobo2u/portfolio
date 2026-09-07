# Eunsoo Jo (Lobo) — Portfolio

Responsive personal portfolio for **Eunsoo Jo (Lobo)**, an AI / Computer Vision developer.

Live site: [https://lobo2u.github.io/portfolio/](https://lobo2u.github.io/portfolio/)

This is a single-page static site (HTML, CSS, and a small JS file). The PDF is no longer the main experience — it is available only as an optional download.

## Open locally

Serve the folder (needed for clean relative assets):

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

You can also open `index.html` directly in a browser.

## GitHub Pages

Settings → Pages → Deploy from a branch → `main` / `/` (root).

The published URL is `https://lobo2u.github.io/portfolio/`.

## What’s on the page

- **About** — industrial CV/AI work and a shift into LLM / RAG / local LLM systems
- **Experience** — high-level public summaries only (no employer source code)
- **Projects** — public GitHub repositories with working links
- **Now** — LoboDoc (validation-level description) and a local LLM lab
- **Contact** — `mailto:` email, GitHub, optional PDF download

Navigation uses in-page anchors with smooth scroll. On small screens, the header menu toggles open and closes after a section is chosen.

## Files

| File | Description |
| --- | --- |
| `index.html` | Portfolio page |
| `css/styles.css` | Responsive layout and theme |
| `js/main.js` | Mobile nav and active-section highlighting |
| `portfolio-1440.pdf` | Optional downloadable PDF snapshot |
| `.gitignore` | Local ignore rules |
