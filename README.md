# Grandpa-Piero-Games

A collection of browser games developed by Grandpa Piero.

Most games are **single self-contained HTML files** (CSS + JS embedded) —
just open the file in any browser, no build step, no dependencies.

## Background

These games were mostly developed **one-shot** during Grandpa Piero's coding model evaluations, with the goal of creating something hopefully amusing to play and fun to improve alongside his grand nephews.

## Play

1. Download or clone this repo.
2. Open any file in `games/` directly in your browser (double-click, or
   File → Open). That's it.

## Games

| Game                                 | File                                                  | Description                       |
|--------------------------------------|-------------------------------------------------------|-----------------------------------|
| Tower Defense                        | `260602 - Tower Defense.html`                         | Classic tower defense, first take |
| 3D Browser Racer                     | `260616 - 3D Browser Racer.html`                      | 3D racing in the browser          |
| Infinite Minecraft World             | `260616 - Infinite Minecraft World.html`              | Endless voxel sandbox             |
| Pac-Man                              | `260616 - PacMan.html`                                | Maze-chomper classic              |
| Neon Tower Defense                   | `260616 - Tower Defense.html`                         | Tower defense, neon variant       |
| 4-Way Traffic Intersection Simulator | `260620a - 4-Way Traffic Intersection Simulator.html` | Intersection sim, run a           |
| 4-Way Traffic Intersection Simulator | `260620b - 4-Way Traffic Intersection Simulator.html` | Intersection sim, run b           |
| 4-Way Traffic Intersection Simulator | `260620c - 4-Way Traffic Intersection Simulator.html` | Intersection sim, run c           |
| 4-Way Traffic Intersection Simulator | `260621 - 4-Way Traffic Intersection Simulator.html`  | Intersection sim, next-day take   |
| Tetris                               | `260710 - Tetris.html`                                | Tetris, first take                |
| Tetris                               | `260711 - Tetris.html`                                | Tetris, second take               |
| Tetris                               | `260711 - Tetris - sonnet5.html`                      | Tetris, Sonnet-5 variant          |
| Serene Flight                        | `260713 - Endless_flight_simulator.html`              | Endless flight simulator          |
| Star Fox                             | `260729 - Star Fox.html`                              | Space combat shooter              |
| Tower Defense                        | `260729 - Tower Defense.html`                         | Tower defense, late-July take     |
| Mario Bros 2D                        | `260909 - Mario_Bros_2d.html`                         | 2D platformer                     |
| Tower Defense                        | `260911 - Tower Defense - cybertiel.html`             | Tower defense, cybertiel variant  |
| BULWARK                              | `260913 - Bulwark.html`                               | Grid-line tower defense           |
| BULWARK (Prompt spec)                | `260913 - Bulwark_recreation_prompt.md`               | Recreation prompt spec for Bulwark|
| Sliding Puzzle                       | `260918 - 15_Game.html`                               | Classic 15-puzzle                 |
| Asteroid Garden                      | `261003 - Asteroid Garden.html`                       | Arcade gardening in space         |
| Rooftop Runner                       | `261003 - Rooftop Runner.html`                        | Endless runner across rooftops    |
| Frostpop                             | `261013 - Frozen Bubbles.html`                        | Frozen-Bubbles-style shooter      |

## Repo layout

```text
games/    one HTML file per game (self-contained)
assets/   shared assets (images, sounds) if a game ever needs them
```

## Adding a game

1. Drop the HTML file into `games/` (e.g. `games/my-game.html`).
2. Add a row to the table above.
3. Commit: `git add games/my-game.html README.md && git commit -m "Add my-game"`
