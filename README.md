# Maze Solver
A maze solver app that takes a maze in the form of a .txt file as input and uses Breadth First Search (BFS) algorithm to find the shortest path from the starting point to any of the multiple exits.

## Usage
To use the app, simply upload your maze file (in .txt format) using the "Choose File" button. Then, click the "Solve" button to see the solution.

## Maze Input Format
In the maze file, the following characters represent:

- `#`: block
- `(whitespace)`: movable space
- `E`: exit
- `^`: starting position

## Demo
A demo of the app is available at https://datpt98.github.io/maze-solver/.

## Algorithms
- Breadth First Search (BFS): is a graph traversal algorithm that visits all the vertices of a graph in breadth-first order. In other words, it visits all the vertices at distance 1 from the starting point, then all the vertices at distance 2, and so on, until it finds the exit.
- *Backtracking (optional)*: is a algorithmic technique where possible solutions are incrementally constructed and tested. If a solution cannot be completed, the algorithm "backtracks" to a previous point and tries a different path. In the case of this app, backtracking was not used since it does not necessarily find the shortest path in the maze.


## Credits
This app was created using plain HTML, CSS, and JavaScript by Daniel.