# PDAce and aPDAce for Convex-Concave Saddle-Point Problems with Nonlinear Coupling Term

This repository contains the official MATLAB and Python implementation for the paper: **"A New Primal-Dual Algorithm with Convex Combination and Extrapolation for Convex-Concave Saddle-Point Problems with Nonlinear Coupling Term"**.

## Overview
This repository provides the code for the **PDAce** (Primal-Dual Algorithm with Convex combination and Extrapolation) and its accelerated version **aPDAce**. These algorithms are designed to solve the following convex-concave saddle-point problem with a nonlinear coupling function:

$$ \min_x \max_y L(x,y) = f(x) + h(x) + \langle g(x), y \rangle - H^*(y) $$

The core innovations include smoothed linearization at convex combination points and dual extrapolation in the mapping space.

## Requirements
*   **MATLAB**
*   **Python**

## Repository Structure
The numerical experiments are categorized into three compressed archives, corresponding to the test cases in the paper:

*   `code_PDAce_QCQP.rar`: MATLAB scripts and functions for **Quadratically Constrained Quadratic Programming (QCQP)**.
*   `code_PDAce_CCMMG.rar`: MATLAB scripts and functions for **Convex-Concave Minimax Games**.
*   `code_PDAce_SCCMMP.rar`: Python scripts and functions for problems with exponential coupling.

## Usage
To reproduce the experimental results:
1. Clone this repository or download the `.rar` files.
2. Extract the specific archive you wish to test (e.g., `code_PDAce_QCQP.rar`).
3. Open MATLAB or Python and navigate to the extracted directory.
4. Run the main script (e.g., `main01.py` or `test_QCQP.m`).
