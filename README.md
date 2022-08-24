# Introduction
We contribute here a Matlab-based optimization package based on our novel optimization algorithm named Balancing Composite Motion Optimization (BCMO). It is noted that this proposed algorithm is constructed without algorithm-specific parameters, the users can directly apply it to solve any unconstrained optimization problems without tuning special parameters. Some detailed definitions and instructions are also presented into the codes to help the users easily modify it for personal research and uses. We show below some necessary information of our BCMO package including

Structure of BCMO software package:
Main.m: the main function for implementing BCMO to solve unconstrained optimization problems.
OptimProblem.m: the function defining the objective function of unconstrained optimization problems.
BCMO.m: the 100-line Matlab codes of BCMO solver.
How to solve unconstrained optimization problems by BCMO software package:
Define the objective function in OptimProblem.m Define the necessary inputs (dimension, population size, maximum generation, bounds, etc.) in Main.m
Run Main.m and wait until the optimization process done.
Get output

# Contributors
- Thang Le-Duc
- Quoc-Hung Nguyen
- Hung Nguyen-Xuan

# Python version
https://github.com/ThangLe-duc/BCMO_Package_Python

# Funding Agency
Vingroup Innovation Foundation (VINIF) in project code VINIF.2019.DA04

# References
Thang Le-Duc, Quoc-Hung Nguyen, H. Nguyen-Xuan, Balancing Composite Motion Optimization, Information Sciences, 520, 250-270, 2020 https://www.sciencedirect.com/science/article/pii/S0020025520300773
US Patent US20210224576A1 https://patents.google.com/patent/US20210224576A1/en
