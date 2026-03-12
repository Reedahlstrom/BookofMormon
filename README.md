# Book of Mormon RPG (Phaser)

Single-file Phaser 3 RPG prototype (currently `index.html`) with procedurally generated pixel art, UI, lighting/particles, and Web Audio (no external audio files).

## Run

Because this is a browser game, it runs best from a local web server (some browsers restrict features when opening `file://` directly).

From this repo folder:

- Python: `python3 -m http.server 8000`
- Node: `npx http-server -p 8000`

Then open `http://localhost:8000`.

## Controls (Default)

- Movement: Arrow keys
- Interact / advance dialogue: `Space` or click/tap
- Pause menu: `Esc`

## Notes

- Phaser is loaded from a CDN in `index.html`.
- Game state is stored in `GameState` and persisted via `localStorage` (autosave on major transitions).
