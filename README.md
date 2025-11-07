# CI2025_lab2
# EVOLUTIONARY TSP SOLVER
Python implementation of an evolutionary algorithm for finding near-optimal solutions for the Travelling Salesman Problem.
It aims to find the shortest possible route visiting a set of cities and returning bacj to the origin city. This project implements a blend of genetic search and local optimization.

# FEATURES OVERVIEW
It features:
- a hybrid (half random and half greedy tours) initialization for better diversity
- genetic operators such as segmented crossover, swap, inversion and shift mutations
- adaptive mutation rate that increases dynamically when the population stagnates and decreases when improving
- 2-optimum local refinement operating periodically
- automatic batch testing running all .npy files in the lab2 folder

# EXAMPLE OUTPUT
Running test: problem_g_100.npy
Common tests -> negatives: False 
 zero diagonal: True 
 symmetric: True
Evolving: 100%|██████████| 300/300 [00:01<00:00, 150.23it/s]
Finished problem_g_100.npy 
| Cities: 100 
| Best cost: 4171.107

# ACKNOWLEDGMENTS
Based on teaching material by Giovanni Squillero, Politecnico di Torino.
Implementing also making use of LLM for better optimization and refinement.
