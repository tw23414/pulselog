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

---

## Windows installer

The v2 Windows installer has been built successfully.

**[Download the PULSELOG v2 Windows installer](https://github.com/tw23414/pulselog/actions/runs/45096220234)**

Open the workflow run and download the `PULSELOG-Windows-Installer` artifact near the bottom of the page. Extract the ZIP, then run the `.exe` installer inside it.

*Note: GitHub Actions artifacts expire after 30 days. A future permanent installer download should be attached to a GitHub Release.*
