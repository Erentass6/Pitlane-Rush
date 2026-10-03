# Pitlane Rush

A browser-based 3D driving game about building a car, tuning a race, and finding your line. Built with Three.js and vanilla JavaScript; no build step or backend is required.

**Play:** https://erenvelitas.com/pitlane-rush/  ·  **Portfolio:** https://erenvelitas.com/

## Features

- 15 selectable cars and a 3D customization garage
- Seven environments, with day and night settings
- Adjustable grid size, lanes, difficulty, camera, transmission, music, and engine sound
- Procedurally generated road surfaces, lighting, reflections, drift effects, and modular car parts
- Local browser storage for customizations, score, and distance
- Keyboard controls and responsive game interface
- Locally bundled Three.js and audio files; the game can run without fetching game assets from a CDN

## Run locally

Open `index.html` in a current version of Chrome or Edge. If your browser restricts local files, run a static server from this directory:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Controls

| Action | Keys |
| --- | --- |
| Accelerate | W or ↑ |
| Brake / reverse | S or ↓ |
| Steer | A / D or ← / → |
| Nitro | Shift |
| Handbrake / drift | Space |
| Manual gear down / up | Q / E |
| Change race camera | C |
| Pause | Esc |
| Start driving | Enter |

## Credits and third-party notices

The game code and original visual design are © Eren Taş. No license is granted for reuse of the game code unless the author adds one separately. Three.js is distributed under the MIT License; see [`vendor/THREE-LICENSE.txt`](vendor/THREE-LICENSE.txt).

Audio credits:

- “Starting a car and driving” by Stephan, public domain: https://commons.wikimedia.org/wiki/File:Starting_a_car_and_driving.ogg
- Rover V8 by Collard, public domain: https://commons.wikimedia.org/wiki/File:Rover-v8-rr79.ogg
- Ferrari 250 GTO engine sound by Provo rossi, CC BY 4.0: https://commons.wikimedia.org/wiki/File:Ferrari_250_GTO,_Engine_Sound.ogg
- In-game music is generated with Web Audio.
