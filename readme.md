# Sudoku Solver – Java (Backtracking Algorithm)

This project implements a **Sudoku puzzle solver** using the **backtracking algorithm** in Java. It efficiently solves any 9x9 Sudoku board by filling in the empty cells while adhering to standard Sudoku rules.

## Features

- Solves any valid 9x9 Sudoku puzzle
- Uses recursive backtracking with constraint checking
- Runs in console – easy to compile and test
- Clean and modular code (no external libraries required)

## Algorithm Used

The solution is based on the **backtracking** approach:
- Try filling empty cells with digits 1–9
- For each placement, check if the digit is valid (row, column, and 3x3 sub-grid)
- Recursively solve the rest of the board
- Backtrack if no valid digit can be placed


