# sudoku_solver
This is a project which takes an input of the sudoku puzzles as an 81 characters long string containing the digits from 0 to 9, where 0 represents an unfilled cell of the Sudoku Board. The objective of the algorithm is to replace all the zeros with valid digits such that the entire Sudoku Puzzle is solved. For doing this in a conventional way, the processor will require to try all 2*1077 possible combinations in a worst case scenario which is a huge number. So, to solve this problem in a comparatively less time, the Backtracking Algorithm is one of the best solutions to it.
Table of Contents

    Requirements
    Usage
    Future Works
    Send Me Queries or Feedback
    License

Requirements

To download and use this code, the minimum requirements are:

    Python 3.0 and above OR Python 2.2 and above

Usage

Once the requirements are checked, you can easily download this project and use it on your machine in few simple steps.

    STEP 1
    Download this repository as a zip file onto your machine and extract all the files from it.

    Download and Extract Zip Folder

    STEP 2
    Run the solve.py file using python to see the solution

    Run solve.py File Using Python

    NOTE:

    1 - If you are using Linux or Mac you will need to change one line of code. Instructions for which are commented in the same file on line #3.

    2 - The algorithm takes only ~1 second to compute most of the Sudoku Puzzles. It takes more time to show the output on every iteration. So, if you want to skip the visualization part to speed it up, feel free to comment out the lines #28 to #30.

    STEP 3
    You can change last digits of the puzzle0 and solution0 on lines #5 and #6, respectively, to check the algorithm for different puzzles. There are 5 demo puzzles already given in the puzzles.py file and their respective solutions are stored in the solutions.py file. Feel free to add your own puzzles to explore more.

Future Works

This is a basic academic project and I am planning on exploring other ideas to make it more interesting and intuitive. Some of the things I'm working on currently are listed below.

    Trying different algorithms than the Backtracking such as Stochastic search, Constraint programming, Exact cover, and others.
    Exploring the use of Machine Learning algorithms to solve Sudoku Puzzles using a dataset available on Kaggle which provides 9 million Sudoku Puzzle-Solution pairs.
    Using Convolutional Neural Networks and Image processing to detect Sudoku Puzzles from the hard copies and then displaying the found solutions onto it using the AR (Augmented Reality) Technology.
