# Keisyazka Fathaya Putri, portfolio

Static site: `index.html` (home) and `mandiri.html` (micro credit case study).
Content lives in `assets/data.js`; `assets/main.js` renders it.

## Edit in the browser

Open `admin.html` on the live site. Connect GitHub with a fine-grained token that has
access to this repository only and the permission "Contents: Read and write".
Publish commits `assets/edits.js` and new images, and the site redeploys in about a minute.

## Deploy

GitHub Pages serves the `main` branch directly. In the repository settings, set
Pages, Source to "Deploy from a branch", branch `main`, folder `/ (root)`, once.

## Search engines

Every page has `<meta name="robots" content="noindex">`. Remove it from `index.html`
and `mandiri.html` when the site should appear in search results.

Logo credits: `assets/clients/README.md`.
