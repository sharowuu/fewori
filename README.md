# Fewori

Landing page for Fewori — an AI product page builder that turns one product photo into a live sales page.

## Structure

- `index.html` — the landing page served as the site root
- `onlines-home.html` — the same page, kept as the working copy (edit here, then copy to `index.html`)
- `privacy.html`, `terms.html`, `refund.html` — legal pages
- `assets/` — fonts, product photos, UI mockups, demo video and logo marks

Single-file HTML: all CSS and JS are inlined, assets are referenced by relative paths.

## Run locally

Open `index.html` directly, or serve it:

```sh
python3 -m http.server 8000
```
