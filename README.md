# Distributed_Algorithms_for_Finding_Linear_Arrow-Debreu_Market_Equilibria
In this work, we study how to find a linear Arrow-Debreu market equilibrium using distributed update algorithms. We propose different programs based on the convex program formulated by Devanur et al. and solve them with different distributed algorithms. In one of our designs, we transformed the original constrained convex optimization problem into an unconstrained minimax problem using Lagrange multipliers. We then solved it with the optimistic gradient descent ascent algorithm and proved that our proposed solution will eventually converge to market equilibrium and the convergence rate is better than previous studies through theoretical analysis and numerical experimental simulations.