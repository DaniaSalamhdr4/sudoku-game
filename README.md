# sudoku-game

A modern and interactive Sudoku game built using HTML, CSS, and JavaScript.

## Repository Description

This project was developed as part of my training journey at **Bytes4Future**.
The game features a clean and responsive user interface, multiple difficulty levels, real-time validation, timer functionality, and automatic Sudoku generation using the **Backtracking Algorithm**.

The project focuses on:

- Algorithmic problem solving
- Recursive backtracking
- DOM manipulation
- Game state management
- Responsive UI/UX design
- Local Storage usage

---

# Algorithm Used

## Backtracking Algorithm

The Sudoku board is generated using the **Backtracking Algorithm**, a recursive problem-solving technique commonly used for constraint satisfaction problems.

### How it Works

1. Find an empty cell in the grid.
2. Try inserting numbers from `1 → 9`.
3. Check if the number is valid:
   - No duplicate in the row
   - No duplicate in the column
   - No duplicate in the 3×3 box

4. If valid:
   - Place the number
   - Continue recursively

5. If no valid number exists:
   - Backtrack and try another number

This approach guarantees generating a valid Sudoku puzzle.

---

# Game Features

✅ Multiple Difficulty Levels

- Easy
- Medium
- Hard
- Very Hard
- Insane
- Inhuman

✅ Automatic Sudoku Generation

✅ Real-time Error Detection

✅ Interactive Cell Highlighting

✅ Pause / Resume System

✅ Game Timer

✅ Animated UI Effects

✅ Responsive Design for Mobile & Desktop

✅ Local Storage Support

- Stores the player name automatically

✅ Dynamic Sudoku Validation

---

# 🎨 UI / UX Design

## The interface was designed with a **simple, modern, and clean style** to provide a smooth gameplay experience.

# Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

# Project Structure

```bash
sudoku-game/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── static/
```

---

# ▶️ How to Run

1. Clone the repository

```bash
git clone <https://github.com/DaniaSalamhdr4/sudoku-game.git>
```

2. Open the project folder

3. Run `index.html` in your browser

---

# 🎯 Learning Objectives

This project demonstrates:

- Recursive Backtracking Algorithms
- Sudoku puzzle generation
- Grid-based game logic
- DOM manipulation
- Event handling
- Local Storage usage
- Responsive web design
- UI animations using CSS

---

# Demo

```md
![Sudoku Game](./screenshots/game.png)
```

---

# Author

- **Dania Salama** - [DaniaSalamadr4](https://github.com/DaniaSalamhdr4)
