# Algorithms

## NP_complete
High-level algorithms for solving NP-complete problems can be found here, such as:
* a **knapsack problem** solved with exact and inexact algorithms (which can be found in the knapsack file) and with a genetic algorithm.
* the **traveling salesman problem**, the genetic algorithm for which is given in the file. The results are very close to optimal.
* **Quadratic assignment problem** - the solution to which can be found in the implementation of local search with the best improvement and iterative local search
* **Cell formation problem**, the solution of which is implemented using the annealing simulation method, lies in the corresponding file.

And you can also find **substring search algorithms** in a string as the first studied algorithms.

A file called more_algos implements several algorithms:
## Sorts
* Sorts in python and c++, but due to the time it takes to convert to c++, sorts in python work faster, namely:
  1. **Radix_sort**, based on Counting_sort, allows you to sort positive integers by digits in linear time.
  2. **Bucket_sort**, also supposed to run in linear time, but it requires the numbers to be evenly distributed over a certain range
  3. **Quick_sort** running in O(n log n).
  
All these arguments for the time of work can be seen on the graphs.

## Algos on graphs
* Algorithm for finding bridges:
  1. deterministic - based on building DFS with M statistics
  2. randomized - also based on the construction of DFS and random sampling of spanning trees in the graph.

* randomized algorithm for finding 2 bridges - the idea is similar to finding 1 bridges, but the details are different.

The quality of the work of these algorithms can be seen on the graphs, where you can see the speed of work for each algorithm.

* Search for Euler cycles
## Arithmetic
* Arithmetic in finite fields and rings:
  1. advanced euclid algorithm
  2. fast exponentiation by Fermat's little theorem
