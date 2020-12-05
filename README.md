# MU-Puzzle
Solved MIU puzzle using autonomous agents, which utilised breadth-first search, depth limited dfs and iterative deepening search algorithms.

The MU system is presented as a puzzle: can you transform the string MI into the goal
string? In order to accomplish this, you are given the following rules:

Rule 1: If your string ends in an I, you can add a U on the end: xI → xIU

Rule 2: If the string starts with M, you can double what comes after the M: Mx → Mxx

Rule 3: If you have III in a string, you can replace it with a U: xIIIy → xUy

Rule 4: If you have UU in a string, you can delete it altogether: xUUy → xy
