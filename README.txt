# ICT Daily Observation Journal — Android installable PWA

This folder contains the Progressive Web App version of the ICT journal.

## Important
A PWA must be served from HTTPS (or localhost) for Chrome to offer a proper install option. Opening `index.html` directly from File Manager may let you use the journal, but will not reliably enable installation/offline caching.

## Install on Android
1. Upload the contents of this folder to an HTTPS static host (for example, a static site hosting service).
2. Open the hosted `index.html` URL in Chrome on Android.
3. Open Chrome's ⋮ menu and choose **Install app** or **Add to Home screen**.
4. Launch it from the new home-screen icon.

## Data
Journal entries are stored in the browser's local storage on that device. Use the built-in JSON backup and CSV export regularly. Clearing browser/site data can delete saved entries.

## Files
- `index.html` — journal interface
- `manifest.webmanifest` — installable app metadata
- `sw.js` — offline asset cache
- `icon-192.png`, `icon-512.png` — app icons
