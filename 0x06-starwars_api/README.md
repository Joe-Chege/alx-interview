# Star Wars Characters Project

## Overview
The "Star Wars Characters" project is part of the curriculum at Holberton School and focuses on interacting with an external API to fetch and display information about Star Wars characters. The goal is to create a script that prints the characters of a specific Star Wars movie based on the provided Movie ID.

## Project Details
- **Short Specializations**: Algorithm, API, JavaScript
- **Author**: Alexa Orrico, Software Engineer at Holberton School
- **Weight**: 1
- **Project Duration**: Feb 12, 2024, 6:00 AM - Feb 16, 2024, 6:00 AM

## Concepts Needed
To successfully complete this project, familiarity with the following concepts is crucial:
- **HTTP Requests in JavaScript**: Understanding how to make HTTP requests to external services using the request module or alternatives like fetch in Node.js.
- **Working with APIs**: Basics of RESTful APIs, how to interact with them, and parsing JSON data returned by APIs.
- **Asynchronous Programming**: Managing asynchronous operations with callbacks, promises, and async/await syntax. Handling API response data asynchronously.
- **Command Line Arguments in Node.js**: Using the process.argv array to access command-line arguments passed to a Node.js script.
- **Array Manipulation and Iteration**: Iterating over arrays, manipulating data structures to format and display character names.

## Additional Resources
For further learning and preparation, consider exploring a [Mock Technical Interview](#) to enhance your skills.

## Requirements
### General
- **Allowed editors**: vi, vim, emacs
- **Environment**: Ubuntu 20.04 LTS, Node (version 10.14.x)
- **File Endings**: All files should end with a new line
- **Shebang**: The first line of all files should be exactly `#!/usr/bin/node`
- **README.md**: A mandatory README.md file at the root of the project folder
- **Code Style**: Code should be semistandard compliant. Rules of Standard + semicolons on top. Also, follow the AirBnB style.
- **Executable Files**: All files must be executable
- **Variable Usage**: Do not use `var`
- **File Length**: File length will be tested using wc

### More Info
- **Node Installation (version 10)**:
  ```
  $ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
  $ sudo apt-get install -y nodejs
  ```

- **Semi-Standard Installation**:
  ```
  $ sudo npm install semistandard --global
  ```

- **Request Module Installation**:
  ```
  $ sudo npm install request --global
  $ export NODE_PATH=/usr/lib/node_modules
  ```

## Tasks
### 0. Star Wars Characters
- **Score**: 0.0% (Checks completed: 0.0%)
- **Description**: Write a script that prints all characters of a Star Wars movie:
  - The first positional argument passed is the Movie ID (e.g., 3 for "Return of the Jedi").
  - Display one character name per line in the same order as the "characters" list in the /films/ endpoint.
  - Use the Star Wars API and the request module.

Example:
```bash
$ ./0-starwars_characters.js 3
Luke Skywalker
C-3PO
R2-D2
Darth Vader
Leia Organa
Obi-Wan Kenobi
Chewbacca
Han Solo
Jabba Desilijic Tiure
Wedge Antilles
Yoda
Palpatine
Boba Fett
Lando Calrissian
Ackbar
Mon Mothma
Arvel Crynyd
Wicket Systri Warrick
Nien Nunb
Bib Fortuna
```

## Repository Information
- **GitHub Repository**: [alx-interview](#)
- **Directory**: 0x06-starwars_api
- **File**: 0-starwars_characters.js

## Copyright
Copyright © 2024 ALX, All rights reserved.