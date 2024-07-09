# PRODIGY_SD_04

Create a program that solves Sudoku puzzles automatically. The program should take an input grid representing an unsolved Sudoku puzzle and use an algorithm to fill in the missing numbers.
It should use backtracking or other suitable techniques to explore possible solutions and find the correct arrangement of numbers for the puzzle. Once solved, the program should display the completed Sudoku grid.

EXPLAINATION:
Define the Sudoku Grid: Represent the Sudoku puzzle as a 2D array, where empty cells are denoted by 0.
Check Validity: Implement a function to check if placing a number in a given cell is valid according to Sudoku rules (no duplicates in the row, column, or 3x3 sub-grid).
Solve using Backtracking: Implement the backtracking algorithm to try placing numbers from 1 to 9 in each empty cell. If a number placement is valid, recursively attempt to solve the rest of the grid. If a conflict arises, backtrack by resetting the cell and trying the next number.
Display the Grid: Once the grid is completely filled, print the solved Sudoku grid.
