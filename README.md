# Gradient Descent: Manual Calculations to Python Implementation

This repository contains a Jupyter Notebook demonstrating **gradient descent** step-by-step, starting from manual/handwritten calculations and converting them into clean, executable Python code.

## Project Overview

- **Dataset**: Simple 2-point linear regression  
  - Point 1: (x=1, y=3)  
  - Point 2: (x=3, y=6)

- **Goal**: Find slope (m) and intercept (b) that minimize Mean Squared Error (MSE) using gradient descent

- **Starting point**: m = -1, b = 1, learning rate α = 0.1

- **Approach**:
  - Manual calculations
  - Step-by-step Python implementation mirroring every manual step
  - No black-box functions — updates, predictions, errors, and gradients are computed explicitly
  - Visualization of parameter convergence (m & b) and error reduction (MSE)

## Files

- `gradient_descent_manual_to_code.ipynb`  
  → Main notebook with:
  - Data & initialization
  - Manual-style gradient descent loop (4 iterations to match hand calculations)
  - Predictions, errors, gradients, and parameter updates printed at each step
  - Optimization of m and b using Scipy
  - Side-by-side plots: parameter changes (m & b) and MSE decrease
  - Summary table

## How to View

1. Click the notebook file directly on GitHub — it renders code, markdown, outputs, and plots automatically.
2. Or clone locally and open in VS Code / JupyterLab:
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
code .
```
text## Key Results (after 4 iterations)

- Final parameters ≈ m = 1.3336, b ≈ 1.8968
- Predictions close to targets: ≈ (3.23, 5.90) vs actual (3, 6)
- MSE decreases significantly from ~36.5 → ~0.035

The notebook shows the full convergence process with printed intermediates and plots.

Feel free to fork or use as a reference for understanding gradient descent!

---
Created by **Francis Mutabazi**  — February 2026
