# Mote's Warehouse — walk-through + campus map

Snapshot of the Claude artifact **Warehouse Walk-through** (https://claude.ai/artifact/TCZRGeBvnZZNYddssag1Qs), saved 2026-11-24.

- `index.html` — the warehouse walk-through (51 lost objects). The bracket button **campus map** in the bottom-right corner opens `campus.html` over the room.
- `campus.html` — Mote's campus: OpenStreetMap buildings and ground drawn as thin grainy ink, shadows that turn with the camera, and dust clusters growing on 조형관 · 성곡도서관 · 북악관 (+ off-hub).
- `fonts/` — Cayetano Round (title), NanumBarunGothic subset, Helvetica Neue subset.
- `img/` — the 39 object photos used by the warehouse.

Open it through a local web server (e.g. `python3 -m http.server`), because `campus.html` is loaded into an iframe and the pages load their fonts and images by relative path.

Map data © OpenStreetMap contributors (ODbL).
