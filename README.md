# Gilles Kindt — Résumé

A responsive personal résumé website, built with semantic HTML and CSS and hosted free on GitHub Pages.

## Website

https://gilleskindt.com/

## Editing

- `index.html`: résumé content, navigation, and contact details.
- `styles.css`: layout, colors, responsive behavior, and print styles.
- `favicon.svg`: browser icon.
- `assets/logos/`: locally served organization logos; see `SOURCES.md` in that folder for provenance.

No build step or JavaScript dependency is needed. Open `index.html` in a browser, or run `python3 -m http.server 8000` in this directory and visit http://localhost:8000.

GitHub Pages publishes the root directory of the `main` branch. Push changes to `main` to update the website. In GitHub, this is configured under **Settings → Pages → Deploy from a branch → main / (root)**.

Content is based on the supplied 2026 résumé. The original PDF, street address, and phone number are intentionally excluded from the public repository. The email address and town are included. Dates are preserved as supplied, including the March–November 2026 Tectonic role.

Fonts are requested from Google Fonts with local system font fallbacks. The site has no analytics, cookies, or tracking scripts.
