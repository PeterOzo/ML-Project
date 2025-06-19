# ML-Project

## Advanced Machine Learning - Constrained Optimization

This repository contains the implementation and solutions for Lab 3 of the Advanced Machine Learning course, focusing on constrained optimization techniques in machine learning. The lab explores fundamental optimization concepts including linear programming, quadratic programming, and Lagrange multipliers through practical applications.

📋 Overview

This lab demonstrates the application of constrained optimization methods to solve real-world machine learning problems. The exercises cover theoretical foundations and practical implementations of optimization algorithms that are essential for understanding advanced machine learning techniques.

🎯 Learning Objectives

Understand Constrained Optimization: Learn how to formulate and solve optimization problems with constraints using Lagrange multipliers
Linear Programming Applications: Explore resource allocation problems and their applications in machine learning
Quadratic Programming: Implement Support Vector Machine (SVM) optimization using quadratic programming techniques
Visualization: Create insightful visualizations to understand optimization landscapes and solution spaces

📁 Repository Contents
Core Files

Lab 3 (1).ipynb: Main Jupyter notebook containing theoretical examples and implementations

Linear Programming for Resource Allocation
SVM implementation using Linear and Quadratic Programming
Practical examples with scikit-learn and cvxopt
Visualization of optimization problems and solutions


Advanced Machine Learning Lab 3 --- Module 1.pdf: Official lab assignment document containing:

Detailed exercise specifications
Mathematical formulations for optimization problems
Submission guidelines and grading criteria



🔧 Key Implementations
1. Linear Programming Example
The notebook includes a comprehensive resource allocation problem demonstrating:

Problem Formulation: Factory production optimization with material and labor constraints
Mathematical Model:

Objective: Maximize profit Z = 40x₁ + 30x₂
Constraints: Material (2x₁ + x₂ ≤ 100) and Labor (x₁ + x₂ ≤ 80)


Implementation: Using scipy.optimize.linprog with visualization of feasible regions

2. Support Vector Machine (SVM)
Multiple approaches to SVM implementation:

Linear SVM: Using scikit-learn with iris dataset
Quadratic Programming Approach: Direct implementation using cvxopt for educational purposes
Visualization: Decision boundary plotting and support vector identification

3. Constrained Optimization with Lagrange Multipliers
Exercise 1 (3 points): Machine learning model parameter optimization

Problem: Minimize cost function J(θ) = 5θ₁² + 3θ₂² subject to constraint 4θ₁ + 2θ₂ - 12 = 0
Solution Approach:

Formulate Lagrangian function L(θ,λ) = J(θ) + λ·g(θ)
Find stationary points by solving ∇θL(θ,λ) = 0
Interpret results in machine learning context



Exercise 2 (2 points): Visualization of optimization landscapes

Create contour plots showing objective function and constraints
Illustrate optimal solution points and feasible regions

🛠 Technologies & Libraries

Python: Core programming language
NumPy: Numerical computations and array operations
SciPy: Optimization algorithms (linprog)
scikit-learn: Machine learning implementations (SVM, datasets)
matplotlib: Data visualization and plotting
cvxopt: Convex optimization library for quadratic programming
Jupyter Notebook: Interactive development environment

📊 Key Features
Mathematical Rigor

Complete mathematical formulations for all optimization problems
Step-by-step derivations of Lagrange multiplier methods
Theoretical background for understanding optimization landscapes

Practical Applications

Real-world examples including factory resource allocation
Machine learning model optimization scenarios
Support Vector Machine implementation from first principles

Comprehensive Visualizations

Constraint visualization with feasible region highlighting
Decision boundary plots for classification problems
Contour plots showing optimization landscapes
Support vector identification in SVM problems

Educational Value

Clear explanations of optimization concepts
Progressive complexity from simple linear programming to advanced quadratic programming
Hands-on implementation encouraging deep understanding
