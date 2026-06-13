# Space Invaders

A browser-based clone of the classic arcade game — a single self-contained HTML file with no dependencies, no build step, and no external assets.

## Play

Open `index.html` in any modern browser. (If published via GitHub Pages, just visit the site.)

## Controls

| Action | Keys |
| --- | --- |
| Move | `←` `→` or `A` `D` |
| Fire | `Space` |
| Pause | `P` |
| Start / Restart | `Space`, `Enter`, or the on-screen button |

## Features

- Classic marching swarm that speeds up as you thin it out, dropping and reversing at the walls
- Three invader types (10 / 20 / 40 points) drawn as pixel sprites, plus a gold **mystery ship** for bonus points
- Four destructible bunkers that erode block-by-block
- 3 lives, escalating waves with faster marching and more aggressive fire
- Score and high score (saved to `localStorage`), particle explosions, a twinkling starfield, and a built-in sound synth (no audio files)

## Tech

Plain HTML5 Canvas + vanilla JavaScript. Everything lives in `index.html`.
