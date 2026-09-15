# NULL_VECTOR¹

A mobile-first, installable PWA with two modes:

### ▸ Arena
A wireframe first-person combat sim (Three.js, r128) — a low-poly "simulation-grid" world with cover buildings assembled from wireframe blocks, wandering hostile bots, and a full COD-style HUD: crosshair, hit markers, health bar with regen, ammo counter with auto-reload, kill feed, minimap, and touch controls (movement joystick, drag-to-look, fire/jump/slide buttons).

### ▸ Claw Drill
A 3-finger claw placement trainer. Reads real multi-touch input (no camera) to verify finger zones for a mobile shooter's MOVE / FIRE / JUMP-SLIDE layout, with a reaction-time drill and live scoring.

## Running it

Open `index.html` on a touchscreen device (desktop won't have multi-touch). For the full app experience, host the folder (GitHub Pages, Netlify, Vercel) and use "Add to Home Screen" — it installs and launches fullscreen like a native app, and works offline via the service worker.

## Structure

- `index.html` — mode-select menu
- `arena.html` — the combat sim
- `drill.html` — the claw trainer
- `manifest.json` / `service-worker.js` — PWA install + offline support
