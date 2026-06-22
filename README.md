# Metropolis-Hastings Hypergraph Partitioner

A Metropolis-Hastings solver for the Hypergraph Patitioning problem, minimizing the number of non-local gates in the quantum circuit corresponding to the given hypergraph.

The current implementation inlcludes
* The basic [Metropolis-Hastings](https://en.wikipedia.org/wiki/Metropolis%E2%80%93Hastings_algorithm) algorithm
* An optimized implementation incorporating [Simulated Annealing](https://en.wikipedia.org/wiki/Simulated_annealing)
* Benchmarking against the [KaHyPar](https://kahypar.org/) hypergraph partitioner
