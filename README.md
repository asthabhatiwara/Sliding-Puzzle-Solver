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

![Screenshot (198)](https://user-images.githubusercontent.com/62290422/124349490-e1be5e80-dc0c-11eb-8cef-4fc6e1d4b062.png)

![Screenshot (200)](https://user-images.githubusercontent.com/62290422/124349497-e84cd600-dc0c-11eb-97e3-b2f7197002a0.png)


## Benchmarking 
+ Bfs and A* took 23 steps in order to solve the given state wherease IDA* took 25 steps more than bfs and A*.<br/>
+ Unlike A*, IDA* does not utilize dynamic programming and therefore it ends up exploring the same nodes many times.<br/>
+ Time execution for IDA-Star 1.598 seconds, A-Star took around 0.07 seconds whereas BFS took around 4.646 seconds to solve this grid.
