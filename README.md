
# CodeAlpha Task 3 - Sudoku Solver

## Project Description
A Sudoku Solver developed using C++ for the CodeAlpha internship.

## Features
- Solves a 9x9 Sudoku puzzle.
- Uses the Backtracking algorithm.
- Checks rows, columns, and 3x3 boxes.
- Displays the puzzle and its solution.

## Technologies Used
- C++
- Backtracking
- Recursion
- Two-dimensional arrays

## Project Files
- sudoku_solver.cpp - Main source code.
- README.md - Project documentation.
- sample_input.txt - Sample Sudoku puzzle.
- sample_output.txt - Expected solved puzzle.
- algorithm.txt - Algorithm explanation.

## How to Compile and Run
Compile using:

```bash
g++ sudoku_solver.cpp -o sudoku_solver
```

Run on Windows:

```bash
sudoku_solver.exe
```

Run on Linux or macOS:

```bash
./sudoku_solver
```

## Algorithm
The program uses recursion and backtracking to fill empty cells with valid numbers from 1 to 9. If a choice leads to an invalid solution, it resets the cell and tries another number.

## Learning Outcomes
- Recursion and backtracking
- Sudoku validation
- Problem-solving using C++

## Internship
CodeAlpha - Task 3
