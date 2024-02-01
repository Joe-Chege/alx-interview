# README.md

## UTF-8 Validation Project

### Overview

This project is a part of the curriculum, specifically the Short Specialization titled "UTF-8 Validation." It is authored by Carrie Ybay, a Software Engineer at Holberton School. The main goal is to implement a Python algorithm that validates whether a given data set represents a valid UTF-8 encoding.

### Project Details

- **Project Weight:** 1
- **Project Start:** Jan 29, 2024, 6:00 AM
- **Project Deadline:** Feb 2, 2024, 6:00 AM
- **Checker Release:** Jan 30, 2024, 6:00 AM
- **Auto Review:** A review will be launched automatically at the deadline.

### Resources

The following resources are recommended for understanding and completing the project:

- UTF-8
- Characters, Symbols, and the Unicode Miracle

### Requirements

#### General

- **Allowed Editors:** vi, vim, emacs
- **Interpretation/Compilation:** Ubuntu 20.04 LTS using Python3 (version 3.4.3)
- **File Endings:** All files should end with a new line
- **First Line:** The first line of all files should be exactly `#!/usr/bin/python3`
- **README File:** A `README.md` file, at the root of the project folder, is mandatory
- **PEP 8 Style:** Code should adhere to the PEP 8 style (version 1.7.x)
- **Executable Files:** All files must be executable

#### Tasks

##### 0. UTF-8 Validation

- **Description:** Write a method that determines if a given data set represents a valid UTF-8 encoding.
- **Prototype:** `def validUTF8(data)`
- **Return:** True if data is a valid UTF-8 encoding, else return False
- **Character Length:** A character in UTF-8 can be 1 to 4 bytes long
- **Data Set:** The data set can contain multiple characters
- **Representation:** The data will be represented by a list of integers
- **Handling Bits:** Each integer represents 1 byte of data; therefore, you only need to handle the 8 least significant bits of each integer

##### Example

```python
#!/usr/bin/python3
"""
Main file for testing
"""

validUTF8 = __import__('0-validate_utf8').validUTF8

data = [65]
print(validUTF8(data))

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))

data = [229, 65, 127, 256]
print(validUTF8(data))
```

Output:

```
True
True
False
```

### Repository Information

- **GitHub Repository:** [alx-interview](link-to-repo)
- **Directory:** 0x04-utf8_validation
- **File:** 0-validate_utf8.py

### Copyright

Copyright © 2024 ALX. All rights reserved.