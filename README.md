# CSCI580_Lauren_Runion
# Assignment 4: TSP with Simulated Annealing and Genetic Algorithm

This assignment solves the same 40 city TSP problem using two methods, Simulated Annealing (SA) with 2-opt moves and a Genetic Algorithm (GA) on permutation tours. Both are compared to a nearest neighbor baseline.

## Files
- TSP_SA_and_GA_Assignment.ipynb: the code, plots, and analysis
- Report PDF: the technical report

## How to run
1. Open the notebook in Jupyter or Google Colab.
2. If matplotlib isn't installed, run `pip install matplotlib`.
3. Run all the cells from top to bottom.
4. Note: run the SA/GA cells before the Part 6 cells, since the plots use data they collect.

## Parameters used
- Cities: 40, seed 7
- SA: 20,000 iterations, start temp 0.2, cooling 0.9995, seed 123
- GA: population 500, 1000 generations, tournament size 3, crossover rate 0.9, mutation rate 0.5, elite size 2, seed 999

## Results
| Method | Best length | Improvement vs NN |
|---|---|---|
| Nearest neighbor | 6.0214 | - |
| SA | 5.0057 | 16.87% |
| GA | 5.3621 | 10.95% |

SA gave the better tour and converged faster. More details are in Part 6 of the notebook and in the report.
