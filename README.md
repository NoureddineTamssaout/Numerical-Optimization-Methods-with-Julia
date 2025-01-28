# Numerical-Optimization-Methods-with-Julia


This repository contains a collection of Jupyter Notebooks that implement and analyze various optimization methods. These methods are essential for solving unconstrained and constrained optimization problems, commonly encountered in scientific computing, machine learning, and high-performance computing. All implementations are done using the **Julia programming language**, known for its high performance in numerical computing.

## Notebooks Overview

1. **`conjugate_gradient_method.ipynb`**:
   - Implements the Conjugate Gradient Method.
   - Designed for solving large-scale linear systems and optimization problems.
   - Provides insights into convergence properties and efficiency.

2. **`armijo.ipynb`**:
   - Demonstrates the Armijo rule for step-size selection in optimization algorithms.
   - Focuses on improving convergence while maintaining numerical stability.

3. **`BFGS.ipynb`**:
   - Implements the Broyden–Fletcher–Goldfarb–Shanno (BFGS) algorithm.
   - A quasi-Newton method for solving unconstrained optimization problems.
   - Includes discussions on approximation of the Hessian matrix.

4. **`kkt.ipynb`**:
   - Explores the Karush–Kuhn–Tucker (KKT) conditions.
   - A method for solving constrained optimization problems.
   - Provides examples and sensitivity analysis of the method.

5. **`least_squares_method.ipynb`**:
   - Implements the Least Squares Method.
   - Suitable for data fitting and solving overdetermined systems of equations.
   - Discusses numerical efficiency and practical applications.

6. **`wolfe_method.ipynb`**:
   - Explores the Wolfe conditions for line search in optimization.
   - Provides practical insights into ensuring sufficient decrease and curvature.
