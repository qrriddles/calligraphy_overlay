# Mindflow Board (v1.1)

A local-first visual mindmapper and flowchart board, written as a single HTML application.

## Features

- Pan and zoom, including two-finger pinch gestures on touchscreens
- Draggable, resizable nodes with shapes, colors, notes, and optional hyperlinks
- Straight, curved, and orthogonal connectors with arrow directions
- Automatic local saving through browser `localStorage`
- JSON backup and restore; PNG and SVG image export
- Mobile export dialog with share/save and preview alternatives

## Deploy on GitHub Pages

1. Create a repository (for example, `mindflow`).
2. Upload `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. Open `https://YOUR_USERNAME.github.io/mindflow/` after deployment.

## Privacy and backups

The app has no backend. Boards are stored in the browser's `localStorage` and are **not synced across devices**. Export JSON backups regularly. Opening the hosted version uses a different storage origin from a local HTML file, so use JSON export/import to migrate existing boards. A public GitHub Pages site exposes the application source, **not** your locally saved boards.

Tailwind CSS is requested from a CDN, but local CSS provides the interface styling when offline. Browser download/share behavior can vary, especially in embedded browsers.

*Vibe-coded with ChatGPT in Oct 2026, for individual use only.*
