# Social Media Performance Dashboard — Game Engine

Static, self-contained dashboard for Game Engine social media performance.

## Contents

- `index.html` — the full dashboard (single file, no build step).

## Views

1. **Social Media Dashboard** — daily gains, weekly and monthly performance,
   platform table, weekly/monthly charts, and insights.
2. **Marketing Content Calendar** — planned and published content grid.

## Hosting

Published via GitHub Pages:

https://mellydeguzman01-ship-it.github.io/social-media-performance-dashboard/

The page is a static snapshot. Data is refreshed by the local Hermes
`Social Dashboard Auto-Generator` job, which regenerates `index.html` from the
Lark Base source of truth and pushes the updated file to this repository.

## Notes

- Charts load `Chart.js` and `chartjs-plugin-datalabels` from jsDelivr CDN.
- All data values are derived from the Lark Base daily-gains tables
  (source of truth). Nothing is inferred or estimated.
