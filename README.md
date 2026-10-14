# Marchitects

Source for the Marchitects website: The Architecture of Trust. Marchitects is a strategic communications and systems development company.

Canonical site: https://www.marchitects.builders/

## Structure

- `index.html` home page
- `about/`, `capabilities/`, `compliance/`, `contact/`, `economic-development/`, `insights/`, `public-sector/`, `who-we-serve/`, `work/` section pages
- `assets/site.css` and `assets/site.js` shared styles and behavior
- `favicon.svg`, `favicon.png`, `apple-touch-icon.png` site icons

## Local preview

The site is static HTML. Serve the folder with any static server:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.
