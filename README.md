# EvolutionaryOptimizer
A simple, robust optimization algorithm to solve multivariate equations or optimize many parameters

The optimizer starts with random parameters and randomly changes these to slowly minimize/maximize the specified function. If a random change makes the new function worse, it is discarded, otherwise, it is kept. The code is set up to solve the quadratic equation (x-1)^2 + (x-2.77)^2 = 0, with the solutions 1 and 2.77.
