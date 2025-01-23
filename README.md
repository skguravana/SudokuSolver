# Sudoku Solver

This project is a **Sudoku Solver** built using **HTML**, **CSS**, and **JavaScript**. It provides a user-friendly interface where users can input a Sudoku puzzle and solve it with the press of a button. The solution is generated using a backtracking algorithm and is visually displayed step-by-step on the board.

## Features
- Interactive grid for entering Sudoku puzzles.
- Highlights invalid entries in red.
- Ensures each number from 1 to 9 is used exactly once in each row, column, and 3x3 box.
- Solves the puzzle using a **backtracking algorithm**.
- Displays the solution visually on the grid.
- Mobile-responsive design for easy usability on smaller screens.


## How to Use
1. Enter the given numbers of the Sudoku puzzle in the grid.
2. Ensure all numbers entered are valid (1–9) and do not violate Sudoku rules.
3. Click the **Solve** button.
4. Watch the grid populate step-by-step with the solution.
5. If the puzzle is unsolvable, an alert will notify you.

## Algorithm
The backtracking algorithm:
1. Finds an empty cell in the grid.
2. Tries placing numbers (1–9) in the cell.
3. Checks if the number is valid according to Sudoku rules.
4. Recursively attempts to solve the rest of the grid.
5. Backtracks if no valid number can be placed.



## Live Demo
*(Provide a link to the live demo if hosted, e.g., GitHub Pages or other platforms.)*

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**

