# SKEIN

**Sport, but for knitting.** Log the yarn and time behind every project and watch it add up — cumulative yarn distance, hours on the needles, pace, a weekly streak, and a shareable card where your project's *shape* stands in for GPS trace.

One self-contained `index.html`. No build step, no server, no accounts.

## Features

- **Dashboard** — lifetime totals (yarn km, hours, avg pace, week streak, projects) plus four hand-drawn SVG charts: cumulative yarn distance, hours per week, knitting pace, and yarn by shape.
- **Projects** — each with a garment silhouette (pullover, cardigan, hat, socks, bag, camisole, shawl, scarf, or a custom shape you draw). Tap a project to expand and edit its sessions.
- **Sessions** — log yarn (metres) and time per sitting; edit the minutes, yarn, or date later, move a session to another project, or delete it.
- **Custom shapes** — draw a silhouette by hand, or upload a pattern PDF to prefill the name and trace its schematic.
- **Share card** — a map card for any project, in your chosen theme, with an optional transparent background for stories and overlays. Saves via the native share sheet on mobile, or downloads a PNG on desktop.
- **Themes** — Vat, Ink, Snow, Heather, Fjord; retints the whole app and the card.
- **Your data stays yours** — everything is stored locally in your browser. Export/import JSON for backups or to move between devices.

## Use it

1. **Log a session** — pick a project, add minutes and metres.
2. **Add a project** — name it and pick a shape (or draw a custom one / draft from a PDF).
3. **Edit** — tap a project's session count to expand, then tap a session to change or delete it.
4. **Share** — open the *Share card* tab, choose a project and theme, and tap *Share / save image*.

## Notes

- The **Share / save image** button uses the native share sheet — test it in a real browser (Safari/Chrome), not an in-app webview.
- Data lives in your browser's `localStorage`, so it is per-browser and per-device. Use **Export data (.json)** to back up or migrate.
- Runtime dependencies load from a CDN (used only for the PDF import): IBM Plex fonts and pdf.js. Nothing else is bundled.

## License

Proprietary — © 2026 Alexandra Elsakova. All rights reserved. Source available for reference and personal use only; see [`LICENSE`](./LICENSE).
