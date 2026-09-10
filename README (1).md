# Circuit // Snake — Web Edition

A classic Snake game built with pure HTML5 Canvas and vanilla
JavaScript — no frameworks, no build tools, no dependencies. Open the
file and play.

## Play it
- **Locally:** just double-click `snake-game.html`, or open it in any
  modern browser (`File → Open`).
- **Live demo:** enable GitHub Pages on this repo (Settings → Pages →
  select the `main` branch) and share the generated
  `https://<your-username>.github.io/<repo-name>/snake-game.html` link.

## Requirements
None. This is a single self-contained HTML file — no `requirements.txt`,
`package.json`, or install step needed, since there are no external
libraries or Python dependencies involved (that's specific to the
separate Python/Pygame version of this project).

## Controls
| Key                    | Action              |
|--------------------------|---------------------|
| Arrow keys / `W A S D`   | Move the snake      |
| `Space`                    | Pause / resume      |
| Swipe (touch devices)    | Move the snake      |
| On-screen d-pad (touch)  | Move the snake      |

## Features
- Canvas-based rendering with a neon/terminal visual style
- Difficulty ramps up as the snake grows
- Retro synthesized sound effects (eat, start, game over), with a
  mute toggle — built using the Web Audio API, no audio files needed
- High score saved locally in the browser (`localStorage`)
- Responsive layout — playable on desktop and mobile
- Pause/resume support

## Tech stack
HTML5 Canvas, vanilla JavaScript, CSS. No frameworks, no build step.

## Project structure
```
.
├── snake-game.html   # the entire game — markup, styles, and logic
└── README.md         # this file
```

## Related project
A separate Python implementation of the same game (using Pygame and
NumPy) is available at: `python-snake-game` — see that repo if you're
interested in the data-structure/algorithm side of the same concept.
