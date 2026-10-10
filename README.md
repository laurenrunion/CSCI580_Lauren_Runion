# CSCI580_Lauren_Runion
# Assignment 4: TSP with Simulated Annealing and Genetic Algorithm

This project solves a 40 city TSP(Traveling Salesman Problem) problem with Simulated Annealing (SA) and a Genetic Algorithm (GA) and compares them to a nearest neighbor baseline.

## Files
- TSP_SA_and_GA_Assignment.ipynb: code, plots, and analysis
- AI_Assignment_4.pdf: technical report

## How to run
1. Open the notebook in Jupyter or Google Colab.
2. Install matplotlib if needed: `pip install matplotlib`
3. Run all cells from top to bottom.

## Parameters
- SA: 20,000 iterations, start temp 0.2, cooling 0.9995, seed 123
- GA: population 500, 1000 generations, tournament size 3, crossover rate 0.9, mutation rate 0.5, elite size 2, seed 999

## Results
- Nearest neighbor: 6.0214
- SA: 5.0057
- GA: 5.3621
- SA gave the better tour and converged faster. More details are in Part 6 of the notebook and in the report.
