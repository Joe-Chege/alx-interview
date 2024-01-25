# alx-interview - Log Parsing

## Overview

This repository contains a script for log parsing that reads standard input (stdin) line by line, computes metrics, and prints statistics after every 10 lines or upon keyboard interruption (CTRL + C). The script calculates the total file size and the number of lines for each HTTP status code encountered in the log entries.

## Repository Structure

- **Directory:** 0x03-log_parsing
  - **File:** 0-stats.py
    - Contains the implementation of the log parsing script.
  - **File:** 0-generator.py
    - A sample log generator script for testing the log parsing script.
  - **File:** README.md
    - Mandatory README file providing information about the project.

## Task Description

### Log Parsing

#### Learning Objectives:
- Read and parse log entries from standard input.
- Calculate and print statistics based on specified conditions.
- Handle keyboard interruptions.

#### Requirements:
- Scripts interpreted/compiled on Ubuntu 20.04 LTS using Python3 (version 3.4.3).
- PEP 8 style (version 1.7.x) should be followed.
- All files must be executable.
- The README.md file must be present at the root of the project folder.

#### How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alx-interview.git
   cd alx-interview/0x03-log_parsing
   ```

2. Run the log generator script to produce sample log entries:
   ```bash
   ./0-generator.py | ./0-stats.py
   ```

3. Observe the output, which will display the total file size and the number of lines for each HTTP status code encountered.

4. The script will print statistics every 10 lines or upon keyboard interruption (CTRL + C).

## Additional Notes

- The sample log generator script (`0-generator.py`) generates random log entries for testing purposes.
- Keyboard interruption (CTRL + C) is handled gracefully, and the script prints the final statistics before exiting.

**Copyright © 2024 ALX, All rights reserved.**