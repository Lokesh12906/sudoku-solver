# Sudoku Solver

An interactive Sudoku game and solver developed using **Python** and **Pygame**. The project allows users to play Sudoku manually or visualize the solving process using a recursive backtracking algorithm.

---

## Features

* 🎮 Interactive graphical interface built with Pygame
* ⌨️ Keyboard and mouse controls
* 🧩 Recursive backtracking algorithm for solving Sudoku puzzles
* ⚡ Real-time solving visualization
* ✅ Input validation
* ⏱️ Built-in timer and strike counter
* 📋 Clean and modular code structure

---

## Technologies Used

* Python
* Pygame
* Backtracking Algorithm
* Recursion

---

## Project Structure

```text
Sudoku-Solver/
│── GUI.py
│── solver.py
│── requirements.txt
│── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Lokesh12906/sudoku-solver.git
```

Navigate to the project directory:

```bash
cd sudoku-solver
```

Install the required dependency:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python GUI.py
```

---

## Controls

| Key         | Action                         |
| ----------- | ------------------------------ |
| Mouse Click | Select a cell                  |
| 1–9         | Enter a number                 |
| Enter       | Confirm the number             |
| Delete      | Clear selected cell            |
| Space       | Automatically solve the puzzle |

---

## Algorithm

The solver uses the **Backtracking Algorithm** to solve Sudoku puzzles.

1. Find an empty cell.
2. Try numbers from **1 to 9**.
3. Validate the placement according to Sudoku rules.
4. Recursively continue until the puzzle is solved.
5. Backtrack whenever no valid number can be placed.

---

## Future Improvements

* Load puzzles from files
* Multiple difficulty levels
* Puzzle generator
* Hint system
* Dark mode
* Animated solving speed control
* Timer leaderboard

---

## License

This project is open-source and available under the MIT License.
