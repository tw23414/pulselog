# PULSELOG — Version 2

This folder contains the PULSELOG v2 release snapshot.

## Files
- `index.html` — v2 web application.
- `manifest.webmanifest`, `icon.svg`, `sw.js` — install metadata, icon and offline cache.
- `main.cjs`, `package.json` — Electron desktop app and Windows installer configuration.
- `README.md` — v2 feature and usage notes.
- `CHANGELOG.md` — v2 release notes.
- `LICENSE` — project license.

## New in v2
- Installable web app metadata.
- Offline app shell after first online visit.
- Date-specific daily reflections.
- JSON backup import as well as export.
- Electron desktop wrapper and Windows NSIS installer build configuration.

## Run the web app
Open `index.html` in a modern browser. For install and offline features, serve it over HTTPS (GitHub Pages does this).

## Build the Windows desktop installer
From this folder, install dependencies with `npm install`, then run `npm run dist` on Windows (or on a compatible build runner).
