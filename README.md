# Banana Chipso — React + Vite

This is the original Banana Chipso website reorganized as a React + Vite project. The existing page markup, Tailwind utility classes, stylesheet rules, and legacy interaction scripts are preserved as much as possible.

## Requirements
- Node.js 18+ (Node.js 20+ recommended)
- Internet connection for the original Tailwind CDN, Font Awesome CDN, and Google Fonts import.

## Run locally
Open a terminal in this project folder and run:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```

## Structure
- `index.html` — Vite HTML entry
- `src/main.jsx` — React entry point
- `src/App.jsx` — original page and React components
- `src/styles.css` — original stylesheet rules
- `public/legacy-interactions.js` — original non-React interaction/reveal scripts

Note: Tailwind is intentionally kept on its CDN to preserve the original page's existing utility classes without redesigning or reconfiguring them. That means those styles require internet access when running the site.
