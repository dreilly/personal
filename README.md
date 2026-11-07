# daniel reilly

A small, static Astro personal site. Warm paper texture, lowercase type, no client-side JavaScript, and locally hosted fonts.

## Run locally

```sh
npm install
npm run dev
```

## Personalize

Edit `src/data/profile.ts` to change the name, bio, email, and social links. Blank links are hidden; the contact placeholder disappears once you add a link.

The layout is in `src/pages/index.astro`; colors, texture, and spacing are in `src/styles/global.css`.

## Build

```sh
npm run build
npm run preview
```

## Deploy to Cloudflare Pages

Push this project to a GitHub or GitLab repository, then create a Cloudflare Pages project and connect that repository.

- Framework preset: **Astro**
- Build command: `npm run build`
- Output directory: `dist`
- Node.js: **22** (set `NODE_VERSION=22` in the build environment if needed)

This site is fully static: no Cloudflare adapter, functions, database, or paid services are required. Cloudflare gives you a `pages.dev` address; you can attach a custom domain later.

The copyright year is generated at build time.
