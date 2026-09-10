# Void Harvest

A browser-playable dual-stick shooter prototype with progression, weapons, resource processing, a skill tree, and a trading post.

## Run locally

```bash
python3 -m http.server 4173 --directory .
```

Then open `http://localhost:4173` in a browser.

## Deploy

GitHub Pages deployment is configured in [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml). Enable **Settings → Pages → Source: GitHub Actions** in the repository after pushing. Every push to `work` or `main` will publish the static site.
