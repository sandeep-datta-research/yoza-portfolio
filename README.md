# Yoza — Artist Portfolio

A responsive editorial-style artist portfolio with a warm ivory palette, serif typography, artwork category filters, fullscreen gallery viewer, About, Commissions and Contact sections.

## Run locally
This version is a static site; no build step is required. Open `index.html` in a browser or use a local server:

```bash
python -m http.server 8000
```

## Deploy
A GitHub Actions workflow in `.github/workflows/pages.yml` publishes the site to GitHub Pages whenever `main` is updated.

After the first workflow run, check **Settings → Pages** and ensure the publishing source is set to **GitHub Actions**. The expected project URL is:

https://sandeep-datta-research.github.io/yoza-portfolio/

## Before sharing publicly
- Replace the sample Unsplash images in `index.html` with Yoza's own artwork.
- Replace `hello@example.com` with the real contact email (it appears in the contact section and form mailto handler).
- Replace the Instagram placeholder with the artist's actual profile.
- Update the biography and service descriptions to match the artist.

The contact form opens the visitor's default email application; it does not store or transmit form submissions to a server.
