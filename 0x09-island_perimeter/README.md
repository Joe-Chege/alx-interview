# 0x09. Island Perimeter

## Overview
This project involves solving the "Island Perimeter" problem by applying algorithms, data structures, and logical operations on 2D arrays (matrices) in Python. The goal is to calculate the perimeter of a single island in a grid represented by a 2D array of integers. This README provides information about the project, concepts needed, problem-solving strategies, and resources.

## Project Details

- **Project Name:** 0x09. Island Perimeter
- **Author:** Alexa Orrico, Software Engineer at Holberton School
- **Weight:** 1
- **Start Date:** Mar 4, 2024 6:00 AM
- **End Date:** Mar 8, 2024 6:00 AM
- **Checker Release Date:** Mar 5, 2024 6:00 AM
- **Auto Review Deadline:** At the project deadline

## Problem Description
The task involves calculating the perimeter of a single island in a grid, where the grid is represented by a 2D array of integers. The grid consists of cells, each of which is either water (0) or land (1). The perimeter needs to be calculated based on the connectivity of land cells horizontally and vertically. The grid is rectangular, with its width and height not exceeding 100, and is completely surrounded by water.

## Concepts Needed
- **2D Arrays (Matrices):**
  - Accessing and iterating over elements in a 2D array.
  - Navigating through adjacent cells (horizontally and vertically).
- **Conditional Logic:**
  - Applying conditions to determine whether a cell contributes to the perimeter of the island.
- **Counting Techniques:**
  - Developing a method to count the edges that contribute to the island’s perimeter.
- **Problem-Solving Strategies:**
  - Breaking down the problem into smaller tasks, such as identifying land cells and calculating their contribution to the perimeter.
- **Python Programming:**
  - Nested loops for iterating over grid cells.
  - Conditional statements to check the status of adjacent cells.

## Resources
- **Python Official Documentation:**
  - Nested Lists: Understanding how to work with lists within lists in Python.
- **GeeksforGeeks Articles:**
  - Python Multi-dimensional Arrays: A guide to working with 2D arrays in Python effectively.
- **TutorialsPoint:**
  - Python Lists: Explains how to create, access, and manipulate lists in Python, essential for working with a grid.
- **YouTube Tutorials:**
  - Python 2D arrays and lists

By understanding these concepts and utilizing the provided resources, you will be equipped to approach the problem methodically.

## Additional Resources
- Mock Technical Interviews

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All files interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Code should use the PEP 8 style (version 1.7)
- Not allowed to import any module
- All modules and functions must be documented
- All files must be executable

## Tasks
### 0. Island Perimeter (Mandatory)
Create a function `def island_perimeter(grid):` that returns the perimeter of the island described in grid.

- `grid` is a list of list of integers:
  - 0 represents water
  - 1 represents land
- Each cell is square, with a side length of 1
- Cells are connected horizontally/vertically (not diagonally)
- Grid is rectangular, with its width and height not exceeding 100
- The grid is completely surrounded by water
- There is only one island (or nothing)
- The island doesn’t have “lakes” (water inside that isn’t connected to the water surrounding the island)

### Example
```python
grid = [
    [0, 0, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 0, 0],
    [0, 0, 0, 0, 0, 0]
]
print(island_perimeter(grid))  # Output: 12
```

## Repository Information
- **GitHub Repository:** [alx-interview](https://github.com/your-username/alx-interview)
- **Directory:** 0x09-island_perimeter
- **File:** 0-island_perimeter.py