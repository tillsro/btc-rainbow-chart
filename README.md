# BTC Rainbow Chart PWA

Interactive BTC rainbow chart packaged as a static Progressive Web App for GitHub Pages.

## GitHub Pages

After files are uploaded, enable Pages from:

Settings → Pages → Deploy from a branch → main → /root

Expected URL:

https://tillsro.github.io/btc-rainbow-chart/

## Notes

- `index.html` contains the interactive chart.
- `manifest.webmanifest` enables app-style install metadata.
- `service-worker.js` caches the app shell for offline reloads.
- The chart renders immediately from embedded snapshot data, then live data refresh is manual.
