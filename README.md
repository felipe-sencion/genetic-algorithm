Genetic Algorithm implementation in Python

A generic implementation of the Genetic Algorithm. The algorithm is implemented so that it can solve any maximization problem. 

In the following example an AGC object is created with the following parameters

population_size = 32
alleles = 2
generations = 4000
p = 0.02
s is the problem to solve. The problem must be in a class and have a definition for a function named "fitness"
AGC.AGC(population_size, alleles, generations, p, s)
