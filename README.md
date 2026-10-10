# Sentinel Line

Endless tower defense in the browser. Random maps, layered enemies with uncapped armored tiers, two-path tower upgrades, and shareable challenge links.

## Play locally

Open `index.html` in a browser. No build step, no dependencies.

## Deploy

The site is a single static file. Vercel serves `index.html` from the repo root.

1. Import this repo in Vercel (Add New, Project, pick the repo).
2. Framework preset: Other. Build command: none. Output directory: leave empty.
3. Deploy. Every push to `main` redeploys. Every other branch gets a preview URL.

## Challenge links

A link ending in an 8-character map code, such as `/#1073D923`, loads that exact map. The share buttons on the game over screen build these links from the current domain.

## Files

- `index.html`: the whole game. HTML, CSS, and JavaScript inline.
