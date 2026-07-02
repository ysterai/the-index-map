# THE INDEX — World Ledger

Interactive world map plotting every geographic location referenced in THE INDEX's episode outline (episodes 22-1000), geocoded against OpenStreetMap. Pan, zoom, and use the region-grouped list to jump straight to any case file.

Live at: https://ysterai.github.io/the-index-map/

## Regenerating after outline changes

The map is generated from `lore/outline/batch-*.json` in the main project. To rebuild:
1. Re-run the geocoding/merge scripts against the current outline data.
2. Copy the resulting HTML file over `index.html` in this repo.
3. Commit and push — GitHub Pages redeploys automatically.
