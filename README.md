# Castle Siege

A browser-based arcade game — a single self-contained HTML file with no dependencies, no build step, and no external assets. Defend your cannon against waves of fantasy creatures marching down from above.

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
- Three enemy types drawn as pixel sprites:
  - **Goblins** (10 pts) — small and swarming, bottom rows
  - **Orcs** (20 pts) — broad and tusked, middle rows
  - **Trolls** (40 pts) — massive and stone-grey, top rows
- A **dragon** that occasionally swoops across the top for a big bonus
- Four destructible stone walls that crack and crumble block-by-block
- **Cannon on wheels** as the player — rolls left and right, fires cannonballs upward
- 3 lives, escalating waves with faster marching and more aggressive fire
- Score and high score (saved to `localStorage`), particle explosions, a moonlit warm starfield, and a built-in sound synth (no audio files)

## Tech

Plain HTML5 Canvas + vanilla JavaScript. Everything lives in `index.html`.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the full history of changes.
