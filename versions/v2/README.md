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

The project is configured to publish the Windows installer as a standalone `.exe` file on the GitHub Releases page, so you can download it directly without extracting a ZIP.

**[Open PULSELOG v2.0.0 downloads](https://github.com/tw23414/pulselog/releases/tag/v2.0.0)**

On the release page, click the `PULSELOG Setup 2.0.0.exe` asset under **Assets**. If the release is still being built, check back after the GitHub Actions run completes.

**Windows Smart App Control:** The installer is not currently code-signed. Windows may still block it even when downloaded as a direct EXE. A trusted code-signing certificate is needed to establish publisher trust; changing the file format does not remove that warning.
