# 0x08. Making Change

## Project Description

This project, "Making Change," addresses the classic coin change problem using dynamic programming and greedy algorithms. The goal is to determine the fewest number of coins needed to reach a given total amount, given a list of coin denominations. This project challenges you to apply your knowledge of algorithms, particularly focusing on the concepts of greedy algorithms, dynamic programming, algorithmic complexity, and problem-solving strategies.

## Concepts Needed

- **Greedy Algorithms:**
  - Understanding how greedy algorithms work and their suitability for the coin change problem.
  - Recognizing the limitations of greedy algorithms and scenarios where they might not provide the optimal solution.

- **Dynamic Programming:**
  - Basic principles of dynamic programming for solving optimization problems.
  - The concept of overlapping subproblems and optimal substructure in the context of the coin change problem.

- **Algorithmic Complexity:**
  - Analyzing the time and space complexity of algorithms.
  - Striving for solutions with lower complexity to meet runtime constraints.

- **Problem-Solving Strategies:**
  - Breaking down the problem into smaller, manageable sub-problems.
  - Understanding iterative vs recursive approaches to dynamic programming.

- **Python Programming:**
  - Manipulating lists and using list comprehensions.
  - Implementing functions with efficient looping and conditional statements.

## Resources

- **Python Official Documentation:**
  - More Control Flow Tools (for loops, if statements).

- **GeeksforGeeks Articles:**
  - Coin Change | DP-7.
  - Greedy Algorithm to find the Minimum number of Coins.

- **YouTube Tutorials:**
  - Dynamic Programming - Coin Change Problem for a visual and step-by-step explanation of the dynamic programming approach.

By thoroughly understanding these concepts and utilizing the provided resources, you will be well-prepared to tackle the coin change problem. This project not only tests algorithmic skills but also reinforces the importance of choosing the right strategy based on problem constraints.

## Requirements

- **General:**
  - Allowed editors: vi, vim, emacs.
  - All files interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3).
  - All files end with a new line.
  - The first line of all files should be exactly `#!/usr/bin/python3`.
  - A README.md file at the root of the project folder is mandatory.
  - Code should follow PEP 8 style (version 1.7.x).
  - All files must be executable.

## Tasks

### 0. Change comes from within

**Mandatory**

Given a pile of coins of different values, determine the fewest number of coins needed to meet a given amount total.

**Prototype:** `def makeChange(coins, total)`

**Return:** The fewest number of coins needed to meet the total.

- If the total is 0 or less, return 0.
- If the total cannot be met by any number of coins you have, return -1.
- The `coins` parameter is a list of the values of the coins in your possession.
- The value of a coin will always be an integer greater than 0.
- You can assume you have an infinite number of each denomination of coin in the list.

**Example:**

```python
makeChange([1, 2, 25], 37)  # Output: 7
makeChange([1256, 54, 48, 16, 102], 1453)  # Output: -1
```

## Usage

To test the implementation of the `makeChange` function, use the provided `0-main.py` file.

```bash
./0-main.py
```

## Repository

- **GitHub repository:** [alx-interview](https://github.com/your-username/alx-interview)
- **Directory:** 0x08-making_change
- **File:** 0-making_change.py

## License

This project is licensed under the [MIT License](LICENSE).