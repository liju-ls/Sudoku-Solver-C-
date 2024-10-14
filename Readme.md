# Sudoku Solver

This project is a simple Sudoku solver implemented in C++. It uses a backtracking algorithm to solve a 9x9 Sudoku puzzle.

## Table of Contents

- [Overview](#overview)
- [How to Compile](#how-to-compile)
- [How to Run](#how-to-run)

## Overview

This C++ program solves a standard 9x9 Sudoku puzzle using backtracking. It will attempt to fill in the grid by trying each number in each empty cell, backtracking when it encounters an invalid configuration.

## How to Compile

To compile the program using `g++`, run the following command in your terminal:

```bash
g++ sudoku_solver.cpp -o sudoku_solver
```

This will compile the source code into an executable named sudoku_solver.

## How to Run

After compiling, you can run the program by executing the following command:

```bash
./sudoku_solver
```
