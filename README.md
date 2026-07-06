# personal-website

Reyhan Haider's personal website — a single minimal page with name, subtitle, and links.

## Structure

- `index.html` — the entire site (markup + embedded CSS)
- `favicon.svg` — monogram favicon
- No build step, no dependencies. Just static HTML/CSS.

## Local preview

Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Deployed via GitHub Pages from the `main` branch.
