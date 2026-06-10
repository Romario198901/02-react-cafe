# 02-react-cafe

A small React + Vite + TypeScript demo app for recording cafe votes.

## Tech stack

- React 19
- Vite
- TypeScript
- ESLint
- modern-normalize

## Scripts

From `package.json`:

- `npm run dev` — start dev server (vite)
- `npm run build` — compile TypeScript and build for production
- `npm run preview` — preview production build locally
- `npm run lint` — run ESLint across the project

## Getting started

1. Install dependencies:

```bash
npm install
```

2. Run development server:

```bash
npm run dev
```

3. Build for production:

```bash
npm run build
```

4. Preview production build:

```bash
npm run preview
```

## Project structure (key files)

- `index.html` — app entry
- `vite.config.ts` — Vite configuration
- `tsconfig.json` — TypeScript config
- `src/main.tsx` — React entry
- `src/components/` — UI components
  - `App/` — main app
  - `CafeInfo/` — cafe details
  - `Notification/` — notifications
  - `VoteOptions/` — voting options
  - `VoteStats/` — voting statistics
- `src/types/` — shared TypeScript types

## Notes & next steps

- No license specified in repository.
- Consider adding tests, CI, and deployment instructions.

---


