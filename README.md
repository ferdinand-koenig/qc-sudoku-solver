# qc-sudoku-solver
Algorithm to solve sudokus on a Fujitsu Digital Annealing Unit (DAU).

## About
Quantum Computing project for the 4th semester in Computer Science at the DHBW Stuttgart. Solving a Sudoku on a DAU (Digital Annealing Unit) with QUBOs (Quadratic unconstrained binary optimization).

Team: Ferdinand König, Katrin Herold, and Daniel Stanke.

Lecturers: Prof. Dr. Carmen Winter, Dr. Kay Schwieger, Prof. Dr. Gerhard Hellstern, Andreas Rohnfelder, and Markus Kirsch.

[Project on GitHub](https://github.com/ferdinand-dhbw/qc-sudoku-solver)


## Setup
### 1. base shell for Anaconda
Not part of this README.md

### 2. Installing
- [get the Digital Annealing Development Kit (DADK)](https://www.fujitsu.com/de/themes/digitalannealer/get-started/)
- clone repository and go to directory
- build venv (virtual environment)
`python -m venv .venv`
- activate venv (see below)

### 3. Activate venv
| Platform              | Shell      | Command to activate venv            |
|-----------------------|------------|-------------------------------------|
| POSIX (e.g. Linux)    | bash/zsh   | $ `source ./.venv/bin/activate`        |
| Windows               | cmd        | C:\\\> `.\.venv\Scripts\activate.bat`    |
|                       | PowerShell | PS C:\\\> `.\.venv\Scripts\Activate.ps1` |

### 4. Run Jupyter notebook
Run `jupyter notebook` and open link provided in the shell.
