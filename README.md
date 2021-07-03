# Sliding-Puzzle-Solver
Implementation of IDA*, A-star and BFS Algorithms to solve a NxN grid sliding puzzle problem.

## puzzle_state.cpp
This file contains a struct class which describes any puzzle state in the search space.<br/>
It stores the Current State , Goal State , Current Level, Parent State, total cost and functions to calculate heuristic (both Manhattan and misplaced tiles).<br/>
And a backtrack function to print the valid moves/steps which are involved in solving the given state of sliding puzzle.

## Puzzle_solver
This is the main function for solvig sliding puzzle. It takes the input grid(N) as a Initial state and solves the game state using BFS, A* and IDA* search Algorithm.
