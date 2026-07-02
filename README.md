# We're Not Really Strangers — Pass & Play

A single-page, offline-friendly, pass-and-play conversation game. Static site, no build step, no dependencies.

## Files
- `index.html` — the entire app (markup, styles, game logic)
- `icon-180.png`, `icon-192.png`, `icon-512.png` — solid red home-screen icons
- `manifest.json` — web app manifest (name, icons, theme color)

## Deploy
This is a static site — Vercel needs no framework preset and no build command.
Push this repo to GitHub, then import it in Vercel (see main instructions).

## Local preview
Just open `index.html` in a browser, or run any static server, e.g.:
```
npx serve .
```
