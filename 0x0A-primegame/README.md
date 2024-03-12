# Prime Game

## Overview

This project involves solving a competitive game scenario where players strategically remove prime numbers and their multiples from a set of consecutive integers. The goal is to determine the winner of each round based on optimal play. The challenge incorporates concepts such as prime numbers, the Sieve of Eratosthenes algorithm, game theory, and dynamic programming/memoization.

## Concepts Needed

1. **Prime Numbers:**
   - Understanding what prime numbers are.
   - Efficient algorithms for identifying prime numbers within a range.

2. **Sieve of Eratosthenes:**
   - An efficient algorithm for finding all prime numbers up to any given limit.

3. **Game Theory:**
   - Basic principles of competitive games where players take turns.
   - Understanding win conditions and strategies leading to a win or loss.

4. **Dynamic Programming/Memoization:**
   - Using previous results to make future calculations faster.

5. **Python Programming:**
   - Utilizing loops and conditional statements for game logic and algorithms.
   - Arrays and lists for storing integers and tracking removed numbers.

## Resources

### Prime Numbers and Sieve of Eratosthenes:

- [Khan Academy: Prime Numbers](https://www.khanacademy.org/math/pre-algebra/pre-algebra-factors-multiples/pre-algebra-prime-numbers/v/prime-numbers-introduction) - Introduction to prime numbers.
- [Sieve of Eratosthenes in Python](https://www.geeksforgeeks.org/sieve-of-eratosthenes/) - A step-by-step guide to implementing the sieve algorithm in Python.

### Game Theory Basics:

- [Game Theory Introduction](https://www.investopedia.com/terms/g/gametheory.asp) - A simple explanation of game theory and strategic decision-making.

### Dynamic Programming:

- [What Is Dynamic Programming With Python Examples](https://realpython.com/python-thinking-recursively/) - An introduction to dynamic programming with Python examples.

### Python Official Documentation:

- [Python Lists](https://docs.python.org/3/tutorial/introduction.html#lists) - Managing lists in Python, useful for tracking the game state.

By understanding these concepts and utilizing the recommended resources, you'll be well-equipped to approach the problem with a solid understanding of both mathematical and programming challenges.

## Additional Resources

- **Mock Technical Interview**

## Requirements

### General

- Allowed editors: vi, vim, emacs.
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3 (version 3.4.3).
- All files should end with a new line.
- The first line of all files should be exactly `#!/usr/bin/python3`.
- A `README.md` file at the root of the project folder is mandatory.
- Code should adhere to PEP 8 style (version 1.7.x).
- All files must be executable.

## Tasks

### 0. Prime Game

#### Prototype:

```python
def isWinner(x, nums)
```

- `x` is the number of rounds.
- `nums` is an array of `n`.
- Return the name of the player that won the most rounds.
- If the winner cannot be determined, return `None`.
- Assume `n` and `x` will not be larger than 10000.
- Cannot import any packages in this task.

#### Example:

```python
x = 3
nums = [4, 5, 1]
```

1. **First Round:**
   - Maria picks 2 and removes 2, 4, leaving 1, 3.
   - Ben picks 3 and removes 3, leaving 1.
   - Ben wins because there are no prime numbers left for Maria to choose.

2. **Second Round:**
   - Maria picks 2 and removes 2, 4, leaving 1, 3, 5.
   - Ben picks 3 and removes 3, leaving 1, 5.
   - Maria picks 5 and removes 5, leaving 1.
   - Maria wins because there are no prime numbers left for Ben to choose.

3. **Third Round:**
   - Ben wins because there are no prime numbers for Maria to choose.

**Result:** Ben has the most wins.

### Example Usage:

```python
isWinner(5, [2, 5, 1, 4, 3])
# Output: Ben
```

## Repository Information

- **GitHub Repository:** [alx-interview](https://github.com/your-username/alx-interview)
- **Directory:** 0x0A-primegame
- **File:** 0-prime_game.py

## Copyright

Copyright © 2024 ALX, All rights reserved.