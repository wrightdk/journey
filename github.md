repo: johan/world.geo.json
branch: master
path: countries.geo.json

## Last sync
date: 2026-08-20T16:51:08Z

### Updated in this project
- Copied `countries.geo.json` (modern country outlines) and processed it locally into `landmass-data.js` → `map-geo.js`, used purely as a Europe coastline silhouette (no modern borders shown).
- Also explored `aourednik/historical-basemaps` for precise per-year historical border GeoJSON, but those files (1.3MB+ each) exceeded the import size limit; historical era borders in this project are hand-authored simplified shapes instead, not sourced from that repo.

## Screen map
| Screen | Source files |
|---|---|
| Andre Journey.dc.html (base map coastline) | johan/world.geo.json: countries.geo.json |
