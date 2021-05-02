# Genetic-Algortihm-Solution-to-Knapsack-problem
A Genetic Algorithm Solution to the Knapsack Problem in MatLab using the elitist selection process

## The Knapsack Problem

The problem is that we are given an X amount of items, each occupying some specific units of space and
worth some amount of money. We have to figure out which of these items to take (or not take), in
order to keep the total units of space to within a specified maximum, while trying to maximise the
total amount of money your items are worth.
The units of space and the amount for each of the 16 items are:

![Alt text](https://github.com/Paris778/Genetic-Algorthm-Solution-to-Knapsack-problem/blob/main/ScreenShots/Capture.JPG "ItemsAndValues")

For example, if you were to take the 1st, 2nd and 4th items, the total units of space would be 14, and
the total value would be £10.6. You have to take a set of items so that the total units of space is 40
or below, and the total value is as high as it can be. 

## Genetic Algorithms

Genetic Agorithms aim to find an optimal or near-optimal solution to different kinds of problems, faster than a brute-force approach.
They work by establishing a popuation of agents each with a different set of properties (also caled the genotype) which can be mutated and altered. In this example the genotype of each agent is depicting the ID of items this agent chose to put into their sack. 
The evolution usually starts from a population of randomly generated agents, and is an iterative process, with the population in each iteration called a generation. In each generation, the fitness of every individual in the population is evaluated; the fitness is usually the value of the objective function in the optimization problem being solved. The more fit individuals are selected from the current population, and each individual's genome is modified (crossed-over and possibly randomly mutated) to form a new generation. The new generation of candidate solutions is then used in the next iteration of the algorithm. Commonly, the algorithm terminates when either a maximum number of generations has been produced, or a satisfactory fitness level has been reached for the population.


