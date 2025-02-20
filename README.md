---
title: "Virtual File System with image encryption"
description: "A virtual filesystem interface"
author: "Aron Koli"
date: "2025-02-21"
---

# Virtual Database

## Overview
This project implements a virtual filesystem interface that allows users to create, read, update, and delete files and directories. The state of the filesystem is saved and loaded from a PNG image.

## Features
- Create and remove directories
- Create and remove files
- Read and write file contents
- Navigate through directories
- Quick access to the most visited directories

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/virtual-database.git
    ```
2. Navigate to the project directory:
    ```sh
    cd virtual-database
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Run the filesystem interface:
    ```sh
    python FS_interface.py
    ```
2. Use the following commands within the interface:
    - `cd <dir_name/path>`: Change the current directory.
    - `ls`: List all children of the current directory.
    - `mkdir <dir_name/path>`: Create a new directory.
    - `mkfile <file_name/path>`: Create a new file.
    - `rmdir <file_name>`: Remove a directory and all subdirectories.
    - `rmfile <file_name>`: Remove a file.
    - `readfile <file_name>`: Read the contents of a file.
    - `writefile <file_name>`: Write to a file.
    - `quickaccess`: Open the quicksearch interface.
    - `exit`: Exit the interface.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.