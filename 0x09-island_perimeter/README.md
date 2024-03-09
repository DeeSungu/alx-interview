TITLE
0x09. Island Perimeter

Concepts Needed:
2D Arrays (Matrices):

Accessing and iterating over elements in a 2D array.
Understanding how to navigate through adjacent cells (horizontally and vertically).
Conditional Logic:

Applying conditions to determine whether a cell contributes to the perimeter of the island.
Counting Techniques:

Developing a method to count the edges that contribute to the island’s perimeter.
Problem-Solving Strategies:

Breaking down the problem into smaller tasks, such as identifying land cells and calculating their contribution to the perimeter.
Python Programming:

Nested loops for iterating over grid cells.
Conditional statements to check the status of adjacent cells.

Resources:
Python Official Documentation:

Nested Lists: Understanding how to work with lists within lists in Python.
GeeksforGeeks Articles:

Python Multi-dimensional Arrays: A guide to working with 2D arrays in Python effectively.
TutorialsPoint:

Python Lists: Explains how to create, access, and manipulate lists in Python, which is essential for working with a grid.
YouTube Tutorials:

Python 2D arrays and lists

Tasks
0. Island Perimeter
mandatory
Score: 0.0% (Checks completed: 0.0%)
Create a function def island_perimeter(grid): that returns the perimeter of the island described in grid:

grid is a list of list of integers:
0 represents water
1 represents land
Each cell is square, with a side length of 1
Cells are connected horizontally/vertically (not diagonally).
grid is rectangular, with its width and height not exceeding 100
The grid is completely surrounded by water
There is only one island (or nothing).
The island doesn’t have “lakes” (water inside that isn’t connected to the water surrounding the island).
