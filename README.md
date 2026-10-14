# The Ledger Gallery

A first-person gallery maze where every painting is a real moment from crypto history. Fire two shots at a painting to reveal what happened, with a link to read more.

**Hunt mode:** a clue names a painting. Find it before your ammo runs out. Correct finds refill ammo. **Free roam:** wander and read.

Built for twigpine's Project Treetop, round 01 (games).

## Tech
- Custom DDA raycaster on a plain 2D canvas (no WebGL, no engine, no dependencies)
- Procedurally drawn pixel-art paintings, one per fact (no external assets)
- Fixed 16x16 maze (seeded recursive backtracker plus extra loops). The layout and painting positions are identical every run, with a full map and position marker on screen
- Single file: `index.html`

## Run locally
Open `index.html` in a browser.

## Deploy to GitHub Pages
Repo Settings -> Pages -> Deploy from branch -> `main` / root.

## Credits
Inspired by The Galleria by The Florentines. This project shares no code or assets with it.
Facts are written from public history; Wikipedia links open a search for each topic.
