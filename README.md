# 🔴🔵 Takuzu

A browser-based clone of the logic puzzle game **Takuzu** (also known as Binary Sudoku), inspired by [0h h1](https://0hh1.com) by Q42.

🔗 **Live Demo:** [mastartm.github.io/takuzu](https://mastartm.github.io/takuzu/)

---

## How to Play

- Every cell must be either 🔴 red or 🔵 blue
- No more than **2 of the same color** can be adjacent (horizontally or vertically)
- Each row and column must have an **equal number** of red and blue cells (6 each)
- No two rows and no two columns can be **identical**

## Controls

| Action | Result |
|---|---|
| Left click | Empty → 🔴 Red → 🔵 Blue → Empty |
| Right click | Skip 2 steps forward |
| 💡 Hint | Reveals a random empty cell |
| ↩ Undo | Reverts the last move |
| 🔄 New Game | Generates a new puzzle |

---

## Features

- 12×12 grid with auto-generated valid puzzles
- Real-time error detection with warnings
- Undo history
- Hint system
- How to play modal on first load

---

## Tech Stack

- Vanilla JavaScript
- HTML + CSS

---

*Inspired by [0h h1](https://0hh1.com) — a little logic game by Q42, created by Martin Kool.*
