# N Queens

Chess grandmaster Judit Polgár, the strongest female chess player of all time.

The N queens puzzle is the challenge of placing N non-attacking queens on an N×N chessboard. This program solves the N queens problem.

## Usage

```bash
nqueens N
```

- If the user called the program with the wrong number of arguments, print `Usage: nqueens N`, followed by a new line, and exit with the status 1, where N must be an integer greater or equal to 4.
- If N is not an integer, print `N must be a number`, followed by a new line, and exit with the status 1.
- If N is smaller than 4, print `N must be at least 4`, followed by a new line, and exit with the status 1.
- The program should print every possible solution to the problem.
- One solution per line.

## Example

```bash
./0-nqueens.py 4
[[0, 1], [1, 3], [2, 0], [3, 2]]
[[0, 2], [1, 0], [2, 3], [3, 1]]

./0-nqueens.py 6
[[0, 1], [1, 3], [2, 5], [3, 0], [4, 2], [5, 4]]
[[0, 2], [1, 5], [2, 1], [3, 4], [4, 0], [5, 3]]
[[0, 3], [1, 0], [2, 4], [3, 1], [4, 5], [5, 2]]
[[0, 4], [1, 2], [2, 0], [3, 5], [4, 3], [5, 1]]
```

## Requirements

- Allowed editors: vi, vim, emacs
- All files interpreted/compiled on Ubuntu 20.04 LTS using Python3 (version 3.4.3)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- PEP 8 style (version 1.7.*)
- All files must be executable

## Files

- [0-nqueens.py](./0x05-nqueens/0-nqueens.py): Python script to solve the N queens problem.

## Author

Alexa Orrico, Software Engineer at Holberton School

Copyright © 2024 ALX, All rights reserved.