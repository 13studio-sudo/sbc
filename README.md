# SBC Trip Planner — v0.0.6

Single-file trip planner (Map + Calendar, Plan A/B/C…, EN / 日本語 / 中文).

## Deploy on GitHub Pages
1. Create a new GitHub repository (public).
2. Upload everything in this folder (`index.html`, `.nojekyll`, `README.md`) to the repo root.
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
4. After ~1 min the site is live at `https://<user>.github.io/<repo>/`.

## Updating the published plan
Edits are saved in each visitor's own browser. To publish your edits for everyone:
1. In the app click **Export .zip**.
2. Rename the exported `SBC_TRIP_MAP.html` to `index.html` and replace it in the repo.

## Notes
- Needs internet: Leaflet + SortableJS (cdnjs), Esri map tiles, OSRM routing, Nominatim search.
- No build step, no API keys.
