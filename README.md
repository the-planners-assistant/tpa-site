# The Planner's Assistant — site

This is the lightweight marketing site for The Planner's Assistant. The interactive product demo now lives separately at https://demo.theplannersassistant.uk — this repo just links out to it.

## What’s here

- Landing page with CTA to the hosted demo
- Foundations, Pillars, and Architecture pages with modal detail for each module
- Theme toggles, animated background, and markdown rendering for architecture notes

## Getting started

Prereqs: Node 20+ and npm.

```bash
npm install
npm run dev   # http://localhost:3000
npm run build # outputs to dist/
npm start     # static preview of the built site (vite preview) on port 4173
```

## Tech stack

- React 19 + TypeScript, React Router (`HashRouter`), Vite 6
- Styling: Tailwind CSS v4 tokens, CSS variables, Framer Motion, Lucide icons
- Markdown via `react-markdown` with syntax highlighting

## Project structure

- `components/` layout, header/footer, cards, markdown renderer, ambient background
- `pages/` marketing pages and shared content blocks
- `data/architectureModules.ts` modal content for the architecture view
- `contexts/ThemeContext` theme toggle persisted to `localStorage`

## License

Open source – intended for public-good use (AGPLv3).
