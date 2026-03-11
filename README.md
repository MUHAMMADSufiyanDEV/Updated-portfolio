# Sufiyan Portfolio — Vite + React

This repo is a Vite + React conversion of the original static portfolio.

What I changed
- Kept the original head (fonts, Tailwind CDN, Font Awesome, Three.js, GSAP) to preserve visual styling.
- Converted the HTML body into `src/App.jsx` (JSX) and moved the interactive logic (Three.js background, GSAP mouse effect, IntersectionObserver) into a React `useEffect`.
- Added a minimal Vite setup (`package.json`, `vite.config.js`) and entry (`src/main.jsx`).

Quick start

1. Install dependencies:

```powershell
npm install
```

2. Start dev server:

```powershell
npm run dev
```

Notes & next steps
- I preserved the Tailwind CDN approach for speed. If you prefer a build-time Tailwind integration, I can add `tailwindcss` and configure it.
- I left some global CSS in `index.html` to ensure the visual parity; we can extract everything into `src/index.css` on request.
- To enable the Vite React plugin, you may want to install `@vitejs/plugin-react` (optional):

```powershell
npm install -D @vitejs/plugin-react
```

If you want me to run `npm install` and verify the dev server in this environment, tell me and I'll start the install and smoke-test the app.
