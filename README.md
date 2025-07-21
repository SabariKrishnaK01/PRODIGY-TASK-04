PRODIGY-TASK-04 - 🔢 Sudoku Solver (Python)
This program automatically solves standard 9x9 Sudoku puzzles using backtracking, a classic recursive algorithm. It takes an input grid with empty cells (represented by 0s) and fills in the missing numbers while ensuring all Sudoku rules are followed.

🛠️ Features

 - Automatically solves any valid 9x9 Sudoku puzzle
 - Uses recursive backtracking to try all possibilities efficiently
 - Validates each move according to Sudoku constraints
 -  Fast and logical solution finding, not brute-force
 -  Prints the completed grid in a readable format
 -  Easy to modify for visual output or GUI

🧠 Concepts Demonstrated
 - 2D array manipulation
 - Backtracking algorithm (recursive trial and error)
 - Constraint checking: ensures no duplicates in rows, columns, and 3x3 subgrids
 - Loops and recursion for exploring number placements
 - Clean, modular code with helper functions

💻 Sample Input Grid

grid = [
  [5, 3, 0, 0, 7, 0, 0, 0, 0],
  [6, 0, 0, 1, 9, 5, 0, 0, 0],
  [0, 9, 8, 0, 0, 0, 0, 6, 0],
  [8, 0, 0, 0, 6, 0, 0, 0, 3],
  [4, 0, 0, 8, 0, 3, 0, 0, 1],
  [7, 0, 0, 0, 2, 0, 0, 0, 6],
  [0, 6, 0, 0, 0, 0, 2, 8, 0],
  [0, 0, 0, 4, 1, 9, 0, 0, 5],
  [0, 0, 0, 0, 8, 0, 0, 7, 9]
]

✅ Sample Output

5 3 4 | 6 7 8 | 9 1 2
6 7 2 | 1 9 5 | 3 4 8
1 9 8 | 3 4 2 | 5 6 7
---------------------
8 5 9 | 7 6 1 | 4 2 3
4 2 6 | 8 5 3 | 7 9 1
7 1 3 | 9 2 4 | 8 5 6
---------------------
9 6 1 | 5 3 7 | 2 8 4
2 8 7 | 4 1 9 | 6 3 5
3 4 5 | 2 8 6 | 1 7 9

Sudoku Solved Successfully!
