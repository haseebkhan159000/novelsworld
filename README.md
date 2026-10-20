# NovelsWorld

A responsive React + Vite starter website for exploring famous novels. It includes a responsive homepage, search, genre filters, sorting, book detail dialogs, public-domain source links, favorites, a reading list, local progress indicators, theme styling, and a newsletter form demo.

## Requirements
- Node.js 18 or newer
- npm

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

## Production build

```bash
npm run build
npm run preview
```

The production site is written to `dist/`. Deploy that folder/build to Vercel, Netlify, or another static hosting service.

## Important scope notes
- Favorites, reading-list items, and simple progress indicators are stored in the current browser using `localStorage`. They are not synced across devices and will not transfer to another browser.
- The newsletter form is a front-end demo only. Connect a mailing-list provider or a secure backend before collecting real addresses.
- This starter does not include real authentication, a cloud database, or a secured admin dashboard. Those need backend services and authorization rules before public launch.
- The initial catalog is a handpicked sample, not every novel ever published. Some book cover URLs may be unavailable; fallback covers appear automatically.
- Where a public-domain text link is provided, it opens the external source. Copyrighted works are not reproduced in this app. Check the applicable edition and local copyright status before distributing any text.
- Google Fonts and Open Library cover images load from external services when available.

## Project structure

```text
novelsworld/
├── index.html
├── package.json
├── README.md
└── src/
    ├── main.jsx
    └── styles.css
```
