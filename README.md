Description
This repository contains a C++ implementation of a Sudoku solver. The solver uses a backtracking algorithm to fill in the missing numbers in a 9x9 Sudoku board while adhering to the game's rules. The board is represented as a 2D array, and the algorithm ensures that each number (1-9) appears only once per row, column, and 3x3 sub-grid.

Features
Sudoku Solver: Uses a backtracking algorithm to solve a given Sudoku puzzle.
Input Board: Define the initial Sudoku puzzle with 0 representing empty cells.
Output: Displays the solved Sudoku board or indicates if no solution exists.
How It Works
Validation: The solver checks if a number can be placed in a specific cell without violating Sudoku rules.
Backtracking: The solver attempts to place numbers in empty cells recursively and backtracks if a number placement leads to no solution.
Display: The initial and solved Sudoku boards are printed to the console.
