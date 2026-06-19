# New Castle International Corp.

**newcastleinternational.com**

Astro site for NCIC — connecting New Castle County, Delaware to international partners through education, culture, and economic development.

## Stack
- [Astro](https://astro.build) — static site generator
- [Cloudflare Pages](https://pages.cloudflare.com) — hosting & deployment
- No framework dependencies — pure Astro + CSS

## Getting Started

```bash
npm install
npm run dev        # localhost:4321
npm run build      # builds to ./dist
npm run preview    # preview build locally
```

## Deploy to Cloudflare Pages

1. Push this repo to GitHub
2. In Cloudflare Dashboard → Pages → Connect to Git
3. Select this repo
4. Build command: `npm run build`
5. Build output directory: `dist`
6. Done — auto-deploys on every push to main

## Project Structure

```
src/
  components/   Nav, Footer
  layouts/      Base layout
  pages/        index.astro, contact.astro
  styles/       global.css
public/
  favicon.svg
wrangler.toml   Cloudflare config
```

## Contacts

- **NCIC** — info@newcastleinternational.com
- **New Castle County** — newcastlede.gov
# staging Fri Jun 19 04:55:13 UTC 2026
