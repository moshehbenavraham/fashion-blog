# Fashion Blog

Fashion Blog is a Vite, React, and TypeScript site for Vesper, a fashion editorial focused on timeless style, sustainable design, capsule wardrobes, and emerging designers.

## Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui components

## Requirements

- Node.js 20+
- npm 10+

## Local Development

```bash
npm install
npm run dev
```

The development server starts on port 8080 by default.

## Production Build

```bash
npm run build
npm run preview
```

The compiled app is emitted to `dist/` and can be served with standard static hosting tooling such as Nginx, Caddy, Apache, or any static hosting provider.

## Project Notes

- Editorial content lives in `src/data/articles.ts`.
- Shared UI components live in `src/components`.
- Social preview metadata uses the local `public/social-card.svg` asset.
- The project uses standard Vite and npm tooling without vendor-specific build plugins.
