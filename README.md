# Job Scheduling Problem Optimization

This repository contains the implementation and analysis of the Job Scheduling Problem (JSP) in a workshop environment. The goal of this project is to minimize the makespan (total job completion time) while maximizing resource utilization across multiple machines.

## Algorithms Implemented
- **Greedy Algorithm**: A heuristic approach that prioritizes job assignments based on minimizing cumulative processing times.
- **Simulated Annealing**: A stochastic optimization algorithm inspired by the annealing process in metallurgy, used here to find near-optimal solutions to the JSP.
- **Integer Programming (IP)**: Provides an exact solution to the JSP, used as a benchmark to evaluate the performance of the heuristic and metaheuristic methods.

## Key Features
- **Performance Evaluation**: The effectiveness of the Greedy and Simulated Annealing algorithms is compared against the IP solution in terms of accuracy and runtime.
- **Scalability**: The project evaluates different scenarios by varying the number of jobs and machines, demonstrating the scalability of each algorithm.

## Results
The study shows that while the IP solution guarantees optimality, both the Greedy Algorithm and Simulated Annealing provide competitive solutions with significantly lower computational complexity. Simulated Annealing consistently outperforms the Greedy Algorithm in terms of makespan across all tested scenarios.

## Future Work
Potential future improvements include exploring additional optimization techniques like Genetic Algorithms, hybrid approaches, and the incorporation of real-world constraints such as dynamic job arrivals and machine breakdowns.

