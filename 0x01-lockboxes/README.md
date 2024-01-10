# Lockboxes

## Introduction
This project aims to solve the Lockboxes problem, determining whether all the boxes in a collection of lockboxes can be opened or not.

## Task Details
- **By**: Carrie Ybay, Software Engineer at Holberton School
- **Weight**: 1
- **Start**: Jan 8, 2024 6:00 AM
- **End**: Jan 12, 2024 6:00 AM
- **Checker Released**: Jan 9, 2024 6:00 AM
- **Auto Review**: Will be launched at the deadline

## Requirements
### General
- **Allowed editors**: vi, vim, emacs
- **Interpreter/Compiler**: Ubuntu 20.04 LTS using python3 (version 3.4.3)
- **File Ending**: All files should end with a new line
- **First Line**: The first line of all files must be exactly `#!/usr/bin/python3`
- **README.md**: A mandatory file at the root of the project folder
- **Code Documentation**: Code should be documented
- **Code Style**: Follow PEP 8 style guide (version 1.7.x)
- **File Execution**: All files must be executable

## Task Description
### 0. Lockboxes
You have `n` number of locked boxes in front of you. Each box is numbered sequentially from 0 to `n - 1`, and each box may contain keys to other boxes. The goal is to write a method that determines if all the boxes can be opened.
- `canUnlockAll(boxes)`: Function prototype.
  - `boxes`: A list of lists representing the lockboxes.
- Rules:
  - A key with the same number as a box opens that box.
  - All keys are positive integers.
  - There can be keys that do not have corresponding boxes.
  - The first box (`boxes[0]`) is unlocked.
- Return `True` if all boxes can be opened, else `False`.

## Testing
To test the `canUnlockAll` function, you can use the `main_0.py` file provided in the project directory. It contains test cases to verify the correctness of the function with different scenarios.

## Usage
Run the following command in the terminal to test the solution:
```
./main_0.py
```

## Files
- `0-lockboxes.py`: Python file containing the `canUnlockAll` function to solve the lockboxes problem.
- `main_0.py`: Python file for testing the `canUnlockAll` function with different scenarios.

## Repository Information
- **GitHub Repository**: [alx-interview](https://github.com/USERNAME/alx-interview)
- **Directory**: 0x01-lockboxes
- **File**: 0-lockboxes.py

© 2024 ALX. All Rights Reserved.
```
