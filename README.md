# Game of Life (C)

This project was written in C to simulate the Game of Life famously created by mathematician John Horton Conway. The Game Of Life is played on an infinite two-dimensional orthogonal grid of square cells, where each cell is either live or dead. Every cell interacts with its eight neighbors that are either horizontally, vertically or diagonally adjacent. At each step in time, any of the following transitions occur:

1. Any live cell with fewer than two live neighbors dies.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with four or more live neighbors dies.
4. Any dead cell with exactly three live neighbors becomes a live cell. Note that all births and deaths occur simultaneously. Together, they constitute a single generation.

Since this code uses an input file as the games initial state, the user can create any text file and just needs to change the name of the file in Line 10. Currently by default the code is set to read InitialState_1.txt. The code also has a set amount of generations to output to the terminal so it stops after that amount. Lastly, the terminal output is color coded for easy readability.
