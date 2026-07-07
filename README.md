# 💣 Minesweeper Game

A console-based implementation of the classic **Minesweeper** game developed in **C++**. The project recreates the core gameplay mechanics, including random mine placement, recursive cell revealing, flagging, and win/loss detection.

---

## 📖 Overview

Minesweeper is a logic-based puzzle game where the player uncovers cells on a grid while avoiding hidden mines. Each revealed cell displays the number of adjacent mines, helping the player identify safe locations.

This project implements the game entirely in C++ using standard libraries and console-based graphics.

---

## ✨ Features

- 🎲 Random mine generation
- 🗺️ 8 × 8 game board
- 💣 10 hidden mines
- 🔢 Automatic calculation of adjacent mine counts
- 🌊 Recursive flood-fill for empty cells
- 🚩 Flag and unflag suspected mines
- 🏆 Win detection
- ❌ Game Over on mine hit
- 🖥️ Console-based user interface

---

## 🛠 Technologies Used

- C++
- STL Vector
- Recursion
- Random Number Generation
- Console I/O

---

## 📂 Project Structure

```
Minesweeper/
│
├── main.cpp
└── README.md
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/minesweeper-cpp.git
```

### Compile

```bash
g++ main.cpp -o minesweeper
```

### Run

```bash
./minesweeper
```

---

## 🎮 Controls

| Action | Description |
|---------|-------------|
| R | Reveal a cell |
| F | Place or remove a flag |

Example input:

```
3 5 R
```

Reveal the cell at row **3**, column **5**.

To flag a cell:

```
3 5 F
```

---

## ⚙️ Game Logic

1. Randomly places **10 mines** on an **8 × 8** board.
2. Calculates the number of adjacent mines for every non-mine cell.
3. Allows the player to:
   - Reveal cells
   - Flag suspected mines
4. Automatically reveals neighboring empty cells using recursion.
5. Ends the game if a mine is revealed.
6. Declares victory when all safe cells are uncovered.

---

## 🧠 Concepts Demonstrated

- Object-Oriented Programming (basic data structures)
- 2D Vectors
- Recursion (Flood Fill Algorithm)
- Randomized Algorithms
- Conditional Logic
- State Management
- User Input Handling

---

## 📸 Sample Gameplay

```
   0 1 2 3 4 5 6 7
0 |# # # # # # # #
1 |# # # # # # # #
2 |# # # # # # # #
3 |# # # # # # # #
4 |# # # # # # # #
5 |# # # # # # # #
6 |# # # # # # # #
7 |# # # # # # # #
```

---

## 🔮 Future Improvements

- Difficulty levels (Easy, Medium, Hard)
- Timer
- High score tracking
- First-click safety
- Colored console output
- Graphical interface using SFML or SDL
- Save and load game functionality

---

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourusername
