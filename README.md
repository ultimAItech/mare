# MareSphere

Premium maritime consulting website. Shipping Connects.

## Tech Stack

- **Astro 6** - Static site generator
- **Tailwind CSS v4** - Styling
- **Bilingual** - German (DE) and English (EN)

## Development

```bash
npm install
npm run dev
```

Visit `http://localhost:4321` — root redirects to `/de/`.

## Build

```bash
npm run build
```

Output in `dist/`. Deploy to any static host (Netlify, Vercel, GitHub Pages).

## Deployment

Update `site` in `astro.config.mjs` for your domain before building:

```js
site: 'https://your-domain.com',
```

## Structure

- `/de/` - German (default)
- `/en/` - English
- `/de/about`, `/de/services`, `/de/contact`, `/de/agb`
- `/en/about`, etc.
