# quaresma

Static HTML site with five pages: semana_1.html → semana_5.html.

## Build
No build step required — this repository contains static HTML files ready to serve.

## Preview locally
Run a simple HTTP server from the repository root and open http://localhost:8000/:

```bash
python3 -m http.server 8000
```

## Automatic deployment (GitHub Pages)
A GitHub Actions workflow is included at `.github/workflows/pages.yml` that automatically deploys the repository root to GitHub Pages when you push to `main`.

If you prefer manual Pages configuration, enable Pages in the repository settings and select the `gh-pages` deployment (the action will create the Pages deployment for you).

## Local notes
- To change the site edit the `semana_*.html` files and push to `main`.
- To preview with live reload, use the VS Code Live Server extension.
