# Ikera.github.io

Personal site for Ivica Lakatoš.

## Stack

- Plain static HTML/CSS (no Jekyll, no Ruby build step)
- GitHub Pages deployment via GitHub Actions

## Local preview

Run a simple local static server from the repo root, for example:

```bash
python3 -m http.server 4000
```

Then open http://localhost:4000

## Deploy

Push to `main` or `master`.
GitHub Actions workflow `.github/workflows/pages.yml` builds a `dist` artifact and deploys to GitHub Pages.
