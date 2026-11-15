# Yoza — Artist Portfolio

An editorial-style artist portfolio built with React, Vite, React Router and Framer Motion.

## Getting started
```bash
npm install
npm run dev
```

## Production
```bash
npm run build
npm run preview
```

## Customize
- Replace sample artwork URLs and metadata in `src/data/artworks.js`.
- Update the artist name, biography and social links in `src/components/Navbar.jsx`, `src/components/Footer.jsx` and `src/pages/About.jsx`.
- Set the contact email in `src/pages/Contact.jsx`.
- Contact form uses a mailto fallback and requires no backend.

## Deploy
For GitHub Pages, set the Vite `base` in `vite.config.js` to `/yoza-portfolio/`, install `gh-pages`, and add deploy scripts. For a custom domain or Vercel/Netlify, the default base `/` is suitable.

The portfolio uses remote Unsplash demo images. Replace these with your own optimized WebP/AVIF artwork before publishing.
