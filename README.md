# Oyun Salonu — Browser Game Collection

A small arcade of four browser games I designed and built as a personal gift project. Each game runs entirely in the browser: no install, no backend, no build step.

**Play it live: https://yunusilesevval.netlify.com**

## Games

| Game | What it is |
|---|---|
| **Yunuscan Simulator** | A three-button reaction game (love, fight, talk) where the goal is to catch the moving "leave" button. |
| **Yunus & Şevval: 10 Bölüm** | A 10-level game that mixes genres: platformer, maze, driving, aiming and slingshot levels. |
| **Sıfır Stres** | A four-level game about bringing a stress meter down to zero. |
| **Brick by Brick** | A puzzle collection (Sudoku, block puzzle, word path). Each solved level places one brick of a Lego-style cat. Puzzles are in English. |

## Tech

- Plain HTML, CSS and vanilla JavaScript, with each game in a single self-contained file
- HTML5 Canvas rendering with a `requestAnimationFrame` game loop
- Web Audio API for sound (Brick by Brick)
- `localStorage` for saving progress (Brick by Brick)
- Mouse, keyboard and touch input
- Responsive game launcher that scales each game inside an in-page frame, with back, restart and fullscreen controls
- Hosted on Netlify

## Project structure

```
index.html          # Landing page / game launcher
games/              # One self-contained HTML file per game
img/                # Cover images and character art
```

## Run locally

No setup needed. Clone the repo and open `index.html` in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## What I learned

- Designing small, finishable game loops and level progression
- Shipping a complete project end to end, from idea to a live link
- Keeping a project dependency-free so it runs anywhere

## Notes

The games are designed for desktop with keyboard and mouse. The text is mostly in Turkish.

## Author

**Yunus Can Çelik** — [GitHub](https://github.com/) · [LinkedIn](https://linkedin.com/)
