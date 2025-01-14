# Computational Physics I - PHYS 3500K (Spring 2025)

## Introduction
This repository is dedicated to Computational Physics I (PHYS 3500K) at Kennesaw State University. Here, you will find examples and notes pertaining to the course, as well as additional material. 

Note that the repository is meant to evolve during the semester. Solutions to the homework problems will appear in a separate repository: https://github.com/apapaefs/phys3500k_sp25_solutions

## Getting started with the repository

### Option 1: Use this if your are unfamiliar with UNIX-like operating systems, git, Python environments, etc. and for BACKUP purposes: 

You can launch this repository with Binder, where you can execute the code directly. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/apapaefs/phys3500k_sp25/HEAD)

To access the environment necessary to run the course material, you simply need to click the link above. This will generate a docker image with the necessary pre-requisites for the course material. It will also load all the files available in the repository.

*WARNING*: One disadvantage is that any changes will not be saved on the repository! You will need to save them locally! Also, binder is not always available. 

### Option 2 (semi-advanced): Access on KSU's Timur Workstation

You can also get access to KSU's Timur workstation. This will require some knowledge of UNIX/Linux operating systems. The advantage is that this system is fast and should always be available. 

#### Instructions: 

##### Pre-requisites: 

First of all, you will need a terminal emulator (https://en.wikipedia.org/wiki/Terminal_emulator).

For the various operating systems: 

- Windows: You will need to install the "Windows Subsystem for Linux" (WSL), see https://learn.microsoft.com/en-us/windows/wsl/install. It is recommended that you install the ubuntu version of this. 
- MacOS: It comes with a terminal emulator. If you can't find it immediately in your app shortcuts, search for "Terminal" in spotlight. 
- Linux: You should already have a terminal installed by default! 

You will also need to have the GlobalProtect VPN for KSU installed, for Windows/MacOS see https://uits.kennesaw.edu/vpn/index.php and for Linux see https://hpcdocs.kennesaw.edu/vpn-client/linux/ (the latter has not been tested!). 

##### Accessing Timur: 

###### Accessing for the first time: 

First login to the server and clone the repository. Using your terminal: 
```ssh -Y username@timur.kennesaw.edu```
(enter password) 

In your home directory, clone the repositories: 

```git clone https://github.com/apapaefs/phys3500k_sp25.git```

and 

```git clone https://github.com/apapaefs/phys3500k_sp25_solutions.git```

###### To Synchronize the repositories: 

Whenever you need to synchronize the local versions of the repositories with the remote repository:

After logging into timur via ```ssh -Y username@timur.kennesaw.edu```, change into the directory of the repository you wish to synchronize: 

```cd phys3500k_sp25```

```git pull```

Note that if there are changes to the files, then a conflict will be detected. In that case, you can reset the repository by executing:

```git stash```

###### To login to the JupyterHub server:

If you are not on the KSU network while at KSU, you will first need to use the GlobalProtect VPN.

```ssh -N -f -L 8887:localhost:8000 username@timur.kennesaw.edu```

where ```username``` is your username. You will be asked to enter your password (this will be hidden, so don't expect any feedback when typing the password). If you get an error related to the port ```8887```, try another port, such as ```8888``` or ```7777```.

then navigate with your web browser to:

```localhost:8887```,

(or the appropriate port you attached the remote server to as above). 

This will ask you again for your username and password. If you encounter an error once you reach the page, simply click on the banner (upper left) and start the server again.

Open up a JupyterLab file by double-clicking it. This should load the default kernel, which does not have all the packages installed. To make sure you are  using the right kernel, click on the upper-right corner, and choose “Python (CompPhys)”. 

It is recommended that you create new files to write and test code. You can always download the files locally before you submit them. 

### Option 3 (advanced): Your own environment
If you are familiar with git and version control, as well as confident that you can maintain your own Python environment and jupyter, you can go ahead and clone the repository locally: 

```git clone https://github.com/apapaefs/phys3500k_sp25```

To update the repository to the latest version at any instant:

```git pull```

within the directory of the repository. 

## Contents:

<details>
  <summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter1/Chapter1.ipynb">Chapter 1: Hello Whimsical World of Pythonic Physics!</a></summary>
  
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
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter2/Chapter2.ipynb">Chapter 2: To err is human, to really foul things up requires a computer!</a></summary>

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
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter3/Chapter3.ipynb">Chapter 3: Randomness and Random Walks</a></summary>

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
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter4/Chapter4.ipynb">Chapter 4: Numerical Differentiation and Integration</a></summary>

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
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter5/Chapter5.ipynb">Chapter 5: Monte Carlo Methods</a></summary>
  
    - Introduction
    - The Basic Monte Carlo Strategy
        - Variance Reduction
    - Multi-Dimensional Monte Carlo Integration
        - von Neumann Rejection Sampling
        - An Introduction to Monte Carlo Simulations

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter6/Chapter6.ipynb">Chapter 6: Matrix Computing, Trial-and-Error Searching and Data Fitting</a></summary>

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
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter7/Chapter7.ipynb">Chapter 7: Ordinary Differential Equations</a></summary>

    - Introduction
    - Mathematical Preliminaries
    - Dynamic form for ODEs
    - ODE Algorithms
        - Euler's Method
        - Runge-Kutta Methods
        - Applicaiton: Nonlinear Oscillators

</details>

<details>
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter8/Chapter8.ipynb">Chapter 8: An Introduction to Nonlinear Dynamics and Chaos</a></summary>

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
<summary><a href="https://github.com/apapaefs/phys3500k_sp25/blob/main/Chapter9/Chapter9.ipynb">Chapter 9: Boundary Value and Eigenvalue Problems</a></summary>

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




