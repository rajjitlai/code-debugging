# Code Debugging Exercises

A collection of programming exercises across five different languages, designed to help developers practice their debugging skills. Each exercise contains intentional syntax and logic errors that need to be identified and fixed to match a target output.

## Project Structure

The repository is organized by programming language, with each folder containing 10 debugging questions (`q1` to `q10`).

- **C/**: C programming exercises.
- **C++/**: C++ programming exercises.
- **Java/**: Java programming exercises.
- **JS/**: JavaScript programming exercises.
- **python/**: Python programming exercises.

## How it Works

1. **The Code:** Each source file (`q1.c`, `q1.py`, etc.) contains a broken implementation of a pattern-printing algorithm. These include syntax errors, undefined variables, and logical flaws.
2. **The Goal:** Look at the corresponding `.png` file (e.g., `q1.png`) in the same directory. This image shows the exact output the code *should* produce once fixed.
3. **The Task:** Debug the source file until its output matches the target image.

## Getting Started

To begin debugging, navigate to the folder of your preferred language and attempt to compile or run the files.

### Example (Python)
```bash
cd python
python q1.py
```
*Note: You will likely encounter errors immediately. That is by design!*

### Example (C)
```bash
cd C
gcc q1.c -o q1
./q1
```

## Supported Languages
- [x] C
- [x] C++
- [x] Java
- [x] JavaScript
- [x] Python

## Purpose
This repository is ideal for:
- Students learning loop structures and nested logic.
- Developers looking to sharpen their "code-reading" and error-spotting abilities.
- Interview preparation for technical debugging rounds.
