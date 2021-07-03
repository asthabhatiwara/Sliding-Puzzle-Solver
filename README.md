# Sliding-Puzzle-Solver
Implementation of IDA*, A-star and BFS Algorithms to solve a NxN grid sliding puzzle problem.

## puzzle_state.cpp
This file contains a struct class which describes any puzzle state in the search space.<br/>
It stores the Current and Goal State, Parent State, and functions to calculate heuristic (both Manhattan and misplaced tiles).<br/>
And a backtrack function to print the valid moves/steps which are involved in solving the given state of sliding puzzle.

## Puzzle_solver
This is the main function for solvig sliding puzzle.<br/>
It takes the input grid(N) as a Initial state and solves the game state using BFS, A* and IDA* search Algorithm.

## Output
Initial State<br/>
[ 3 8 5 ]<br/>
[ 0 7 1 ]<br/>
[ 2 6 4 ]<br/>
