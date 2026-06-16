# Jooyeong Kwag — Portfolio

Personal résumé / portfolio website. Static site (HTML + CSS + vanilla JS), no build step.

## Local preview
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Structure
- `index.html` — the page
- `styles.css` — styles
- `app.js` — scroll reveals, metric count-up, mobile nav
- `assets/` — favicons (SVG + PNG)

## Deploy — Cloudflare Pages
Connect this repo in Cloudflare Pages with:
- **Framework preset:** None
- **Build command:** *(leave empty)*
- **Build output directory:** `/`

Every push to `main` redeploys automatically.
