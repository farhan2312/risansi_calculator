# NPSH and Suction Line Calculator

A single-page React app (Vite) version of the Risansi Industries NPSH & suction-line
calculator. Live calculation of NPSH available, total head loss, and margin vs. NPSHR.

## Run locally

```bash
npm install
npm run dev
```

Open the printed local URL (default http://localhost:5173).

## Build

```bash
npm run build      # outputs static site to dist/
npm run preview    # preview the production build
```

## Deploy to Vercel

This is a standard Vite project — Vercel auto-detects it. After pushing to GitHub:

1. Import the repo at https://vercel.com/new
2. Framework preset: **Vite** (auto-detected)
3. Build command: `npm run build` · Output directory: `dist`
4. Deploy.

No environment variables or extra configuration are required.

## Project structure

- `index.html` — Vite entry, loads fonts and mounts the React root
- `src/main.jsx` — React bootstrap
- `src/App.jsx` — calculator UI + calculation logic
- `src/index.css` — styles (ported verbatim from the original HTML)
- `public/logo.png` — Risansi logo (also used as favicon)
