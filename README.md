# Signal Orchard

**Game ID:** GAME-001  
**Version:** v0.3 — 100-level campaign and locked level picker  
**Genre:** Puzzle / Strategy  
**Status:** Playable

Turn the relay seeds to carry a beacon's light through a quiet alien orchard. Connect every dormant grove to finish a level. The campaign has 100 sequential levels. The first 18 use hand-laid-out networks; later levels remix those networks with mirrored boards, varied relay rotations, and additional route bends.

Only the first level is open at the start. Finishing a level opens the next one. Use **Levels** above the board to revisit any level already unlocked; locked levels stay unavailable until you complete the previous level.

## Run locally

Open `index.html` in a current desktop or mobile browser. No server, install, account, external font request, or game library is required. The typefaces use local system fallbacks.

## Controls

- **Mouse / touch:** tap or click a relay seed to turn it clockwise.
- **Keyboard:** focus the board, use arrow keys to select a relay, then press Enter or Space to turn it.
- **Reset:** restore the current orchard to its starting arrangement.
- **Sound:** use the music-note button to mute or enable small synthesized cues.

Progress is stored in the browser's local storage on the device. The game does not use a server, ads, analytics, or third-party game services.

## Files

- `index.html` — page and game interface
- `style.css` — responsive layout and visual styling
- `game.js` — puzzles, signal simulation, input, audio, and local progress

