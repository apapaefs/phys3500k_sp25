# Computational Physics I - PHYS 3500K (Spring 2025)

## Introduction
This repository is dedicated to Computational Physics I (PHYS 3500K) at Kennesaw State University. Here, you will find examples and notes pertaining to the course, as well as additional material. 

Note that the repository is meant to evolve during the semester. Solutions to the homework problems will appear in a separate repository: https://github.com/apapaefs/phys3500k_sp25_solutions

## Getting started with the repository

### Default Option: Use this if your are unfamiliar with UNIX-like operating systems, git, Python environments, etc.: 

This course is taught primarily using this repository, conjunction with Binder: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/apapaefs%2Fphys3500k_sp25/HEAD)

To access the environment necessary to run the course material, you simply need to click the link above. This will generate a docker image with the necessary pre-requisites for the course material. It will also load all the files available in the repository.

### Advanced Option: Your own environment
If you are familiar with git and version control, as well as confident that you can maintain your own Python environment and jupyter, you can go ahead and clone the repository locally: 

```git clone https://github.com/apapaefs/phys3500k_sp25```

To update the repository to the latest version at any instant:

```git pull```

within the directory of the repository. 

## Contents:

<details>
  <summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter1/Chapter1.ipynb">Chapter 1: Hello Whimsical World of Pythonic Physics!</a></summary>
  
    - Making Computers Obey
        - Machine Language
        - Shells, Operating Systems and Compilers
        - Programming Warmup
        - Structure and Reproducible Program Design
    - Introduction to Python 
        - What is Python?
        - Aside: Why is it called that?!
        - Jupyter Notebooks, the Gitlab repository and Binder
    - Let's write some code!
    - Control Flow Tools
        - if statements
        - for satatements
        - break and continue Statements, and else Clauses in Loops
    - Defining Functions
    - Data Structures
        - List Methods
        - List Comprehensions
        - Tuples and Sequences
        - Dictionaries
        - Looping Techniques
    - Modules
        - User-Defined Modules
        - Standard Modules and the Standard Library
        - NumPy
        - SciPy
        - Matplotlib (Plotting)
        - Other Useful Modules

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter2/Chapter2.ipynb">Chapter 2: To err is human, to really foul things up requires a computer!</a></summary>

    - Computer Number Representations
        - Introduction to Computer Number Representations
        - Floating-Point Numbers
    - Errors and Uncertainties in Computations
        - Types of Errors
        - Subtractive Cancelation
        - Round-off Errors
        - Round-off Error Accumulation

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter3/Chapter3.ipynb">Chapter 3: Randomness and Random Walks</a></summary>

    - Deterministic Randomness
    - Random Sequences
        - Random Number Generation
        - Generating Randon Numbers of Arbitrary Distributions
    - Random Walks
        - Random Walks: Theoretical Description
        - Digression: Object-Oriented Programming in Python
        - Random-Walk Simulation

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter4/Chapter4.ipynb">Chapter 4: Numerical Differentiation and Integration</a></summary>

    - Numerical Differentiation
        - Introduction
        - The forward-Difference Derivative
        - The Central-Difference Derivative
        - The Extrapolted-Difference Derivative 
    - Error Assessment in Numerical Differentiation
        - Introduction
    - Numerical Integration
        - The Trapezoid Rule
        - Simpson's Rule
        - Gaussian Quadrature
        - Higher-Order Rules
        - Integration Error Assessment
    - Minor Digression: Python functools and partial functions

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter5/Chapter5.ipynb">Chapter 5: Monte Carlo Methods</a></summary>
  
    - Introduction
    - The Basic Monte Carlo Strategy
        - Variance Reduction
    - Multi-Dimensional Monte Carlo Integration
        - von Neumann Rejection Sampling
        - An Introduction to Monte Carlo Simulations

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter6/Chapter6.ipynb">Chapter 6: Matrix Computing, Trial-and-Error Searching and Data Fitting</a></summary>

    - Trial and Error Root Finding
        - Introduction
        - Trial-and-Error Roots via Bisection
        - Newton-Raphson Searching
        - Newton-Raphson with Backtracking
    - Matrix Computing
        - Why Matrix Computing?
        - Classes of Matrix Problems
        - Math Recap: Matrix Multiplication
        - Math Recap: Solving Eigenvalue Problems
        - Practical Matrix Computing
        - Matrices in Python: Python Lists, NumPy Arrays
            - Python Lists
            - NumPy Arrays
        - NumPy's Linalg Package
        - N-Dimensional Newton-Raphson
        - More Matrix Examples
    - Data Fitting
        - Lagrange Interpolation
        - Cubic Spline Interpolation
        - Other Scipy Interpolators
        - Least-Squares Fitting
            - Linear Regression
            - Quadratic Functions
            - Nonlinear Fitting


</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter7/Chapter7.ipynb">Chapter 7: Ordinary Differential Equations</a></summary>

    - Introduction
    - Mathematical Preliminaries
    - Dynamic form for ODEs
    - ODE Algorithms
        - Euler's Method
        - Runge-Kutta Methods
        - Applicaiton: Nonlinear Oscillators

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter8/Chapter8.ipynb">Chapter 8: An Introduction to Nonlinear Dynamics and Chaos</a></summary>

    - Introduction
    - The Importance of being Nonlinear
    - Flows on the Line
        - Fixed Points and Stability
        - Linear Stability Analysis
    - Two-Dimensional Systems
        - 2D Linear Systems
        - Classification of Linear Systems
        - The Phase Plane and Phase Portraits
        - Fixed Points and Linearization
    - The Lorenz Equations and Chaos
        - Simple Properties of the Lorenz Equations
            - Linear Stability of the originally
        - The Definition of Chaos
        - Lorenz Attractor Animation

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/Chapter8/Chapter9.ipynb">Chapter 9: Boundary Value and Eigenvalue Problems</a></summary>

    - Introduction
    - The Numerov Algorithm
    - Direct Integration of Boundary Value Problems
    - Green's Function Solution of Boundary Value Problems
    - Eigenvalues of the Wave Equation
    - The One-Dimensional Schrödinger Equation

</details>

## About the Author

[Andreas Papaefstathiou](https://facultyweb.kennesaw.edu/apapaefs/) is Assistant Professor of Physics at Kennesaw State University. This website was originally created in January 2025 and is updated on a best-effort basis.

## References

- Computational Physics, Problem Solving with Python - Rubin H. Landau, Manuel J. Páez, Christian C. Bordeianu.
- Computational Physics (Fortran Version) - Steve E. Koonin, Dawn C. Meredith. 
- Nonlinear Dynamics and Chaos - Steven H. Strogatz.




