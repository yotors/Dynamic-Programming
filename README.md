# Knapsack Problem Benchmark

This project benchmarks three different algorithms for solving the 0/1 Knapsack problem:

- **Brute Force**
- **Top-Down Dynamic Programming (Memoization)**
- **Bottom-Up Dynamic Programming (Tabulation)**

The results are visualized and analyzed in a Jupyter Notebook.

---

## Project Structure
- `Summary.pdf` - Summary on The theory of dynamic programming by Richard bullman
- `bench.ipynb` — Main Jupyter Notebook containing:
  - Implementations of all three algorithms
  - Random test case generation
  - Benchmarking and timing code
  - Visualization of results
  - Detailed analysis and summary

---

## How to Run

1. **Requirements:**
   - Python 3.x
   - Jupyter Notebook
   - `numpy`, `matplotlib`

2. **Setup:**
   - Install dependencies (if needed):
     ```
     pip install numpy matplotlib notebook
     ```

3. **Usage:**
   - Open `bench.ipynb` in Jupyter Notebook or VS Code.
   - Run all cells to see the benchmark results and analysis.

---

## Algorithms Overview

- **Brute Force:**  
  Recursively explores all possible subsets of items. Exponential time complexity (O(2^n)). Only practical for very small item counts.

- **Top-Down DP (Memoization):**  
  Uses recursion with memoization to avoid redundant calculations. Time complexity is O(n * W), where n is the number of items and W is the knapsack capacity.

- **Bottom-Up DP (Tabulation):**  
  Iteratively builds a DP table. Also O(n * W) time complexity, but generally faster in practice due to iterative structure.

---

## Results Summary

- **Brute Force** is only feasible for small numbers of items due to exponential growth in computation time.
- **Top-Down DP** is much faster and can handle moderate problem sizes efficiently.
- **Bottom-Up DP** is the most scalable and efficient, especially for larger problem sizes.

For detailed results and plots, see the summary and analysis section in the notebook.

---
