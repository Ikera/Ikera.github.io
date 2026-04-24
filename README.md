# ivicalakatos.com

This is my personal portfolio site.

I keep it intentionally simple: plain HTML and CSS, no framework, no build pipeline, no Jekyll.

## Tech

- Static HTML/CSS
- GitHub Pages
- GitHub Actions for deployment

## Run locally

From the project root:

```bash
python3 -m http.server 4000
```

Then open [http://localhost:4000](http://localhost:4000).

## Deploy

I deploy by pushing to `main` (or `master`).

The workflow at `.github/workflows/pages.yml` prepares a `dist/` artifact and publishes it to GitHub Pages.
