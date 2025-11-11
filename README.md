# Programming for (Civil) Engineers

Welcome to the GitHub repository for CEE 244: Programming for Engineers, a course offered by the Department of Civil and Environmental Engineering at UMass Amherst. This course introduces essential programming concepts and practical applications for engineers, using Python as the primary language. The course uses Google Colab as an accessible, cloud-based programming interface. While the examples and exercises are occasionally tailored to Civil Engineering contexts, the foundational programming concepts covered are broadly applicable and beneficial for all engineers.

If you are an instructor, please reach out to me and I can also share lab/homework assignments.

Initially created for Fall 2024 Semester. 

## Table of Contents

- [Overview](#overview)
- [Modules](#modules)
  - [P1: Python Basics and Data Types](#p1-python-basics-and-data-types)
  - [P2: Flow Controls](#p2-flow-controls)
  - [P3: Functions and Classes](#p3-functions-and-classes)
  - [P4: Modules](#p4-modules)
  - [P5: Plotting and Data Analysis](#p5-plotting-and-data-analysis)
  - [P6: Linear Algebra](#p6-linear-algebra)
  - [P7: Symbolic and Numerical Mathematics](#p7-symbolic-and-numerical-mathematics)
  - [P8: Introduction to Machine Learning](#p8-introduction-to-machine-learning)
  - [P9: Statistical Simulations](#p9-statistical-simulations)
- [Applications](#applications)
  - [Double Pendulum Animation in Python](#1-double-pendulum-animation-in-python)
  - [Eight Queens Puzzle Solver](#2-eight-queens-puzzle-solver)
  - [Sudoku Solver](#3-sudoku-solver)
  - [Large Language Models Demo](#4-large-language-models-demo)
  - [Truss Analysis](#5-truss-analysis)
- [How to Use](#how-to-use)
  - [Method 1: Clone](#method-1-clone)
  - [Method 2: Open Directly in Google Colab](#method-2-open-directly-in-google-colab)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains lecture materials, code examples, and exercises designed to teach students the fundamentals of programming and its application in solving engineering problems. Each module introduces new concepts and includes practical examples and exercises.

## Modules

### P1: Python Basics and Data Types
**Description:**  
Introduces Python syntax, basic operations, data types (integers, floats, strings, and lists), and variable usage. The module emphasizes foundational concepts necessary for programming logic and computation.  
**Topics:**
- Arithmetic operations
- String manipulation
- Input/output operations
- Lists and basic data structures  

### P2: Flow Controls
**Description:**  
Explores flow control statements like conditional statements (`if`, `else`, `elif`) and loops (`for`, `while`) to build logic in programs.  
**Topics:**
- Boolean operations and comparison operators
- Conditional statements
- Loop structures
- Nesting and combining conditions  

### P3: Functions and Classes
**Description:**  
Introduces modular programming through functions and object-oriented programming basics with classes. Explains code reusability and structure.  
**Topics:**
- Defining and using functions
- Function arguments and return values
- Classes and objects
- Methods and constructors  

### P4: Modules
**Description:**  
Covers the concept of Python modules to organize code. Includes importing standard and custom modules and using library functionalities.  
**Topics:**
- Importing and using modules
- Exploring Python Standard Library
- Creating custom modules  

### P5: Plotting and Data Analysis
**Description:**  
Focuses on data visualization and analysis using Python libraries such as `matplotlib` and `seaborn`. Demonstrates creating various plots and performing statistical analysis.  
**Topics:**
- Line, scatter, and bar plots
- Histograms and distributions
- Subplots and annotations
- Introduction to `pandas` for data manipulation  

### P6: Linear Algebra
**Description:**  
Explores linear algebra concepts and their implementation using `numpy`. Essential for solving engineering and scientific problems.  
**Topics:**
- Vectors and matrices
- Matrix operations (addition, multiplication, dot product)
- Solving linear equations  

### P7: Symbolic and Numerical Mathematics
**Description:**  
Introduces symbolic computation with `sympy` and numerical methods for solving mathematical problems.  
**Topics:**
- Symbolic expressions and simplification
- Solving equations symbolically
- Numerical evaluations and approximations  

### P8: Introduction to Machine Learning
**Description:**  
Introduces basic machine learning concepts and techniques using `sklearn`. Covers simple models like linear regression and explores overfitting and testing.  
**Topics:**
- Linear regression, logistic regression, neural networks
- Training and test datasets
- Mean Squared Error (MSE) evaluation  

### P9: Statistical Simulations
**Description:**  
Covers statistical simulation techniques to model uncertainty and variability in engineering systems.  
**Topics:**
- Monte Carlo simulations
- Random number generation
- Risk and uncertainty analysis  

## Applications


There are some applications in the applications folder. There could be more than the ones listed here. 

### 1. Double Pendulum Animation in Python
Simulates and animates a chaotic double pendulum system resembling a stick figure named "Freddy." This demonstration showcases the principles of chaotic motion through matplotlib animations.  
**Key Features**:
- Models physics with parameters like gravity, pendulum lengths, and initial angles.
- Animates stick figure components (head, arms, legs) using double pendulum equations.  
[Learn more here](https://medium.com/@egemenokte/double-pendulum-freddy-creating-a-dancing-stick-figure-with-python-7cb5e0c94154).

---

### 2. Eight Queens Puzzle Solver
Solves the classic Eight Queens problem using a recursive backtracking algorithm. The goal is to place eight queens on a chessboard without conflicts.  
**Key Features**:
- Validates queen placements using row, column, and diagonal checks.
- Visualizes solutions on a chessboard with seaborn heatmaps.  
[Learn more here](https://medium.com/@egemenokte/solving-the-8-queens-puzzle-recursively-with-python-6440078b68ad).

---

### 3. Sudoku Solver
Solves Sudoku puzzles again using a recursive algorithm. It can solve any Sudoku puzzle as long as there is a valid solution.  
**Key Features**:
- Starts by checking if placement of a given number is valid for a cell.
- Iteratively calls itself to solve a smaller version of the problem.  

---

### 4. Large Language Models Demo
Interacts with an open-source language model (Llama 3.1) via a user-friendly interface. Experiment with the system and user prompts to observe changes in responses.  
**Key Features**:
- Configure system behavior with custom prompts.
- Explore real-time interaction with an advanced language model.  
[More details on Llama 3.1](https://github.com/ollama/ollama).

---

### 5. Truss Analysis 
Analyzes internal forces in truss structures using principles of statics. This application calculates member forces, reactions at supports, and visualizes the results.  
**Key Features**:
- Defines nodes, edges, supports, and loads for a truss.
- Solves statically determinate trusses with equilibrium equations.
- Visualizes the structure and annotated forces.  

This tool serves as an educational resource for courses in statics and structural analysis, helping students understand force distribution in truss systems.

---

## How to Use

### Method 1: Clone

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/CEE244-Programming-for-Engineers.git
   ```
2. Navigate to the relevant module folder.
3. Open the `.ipynb` files in Jupyter Notebook or Google Colab.
4. Follow the instructions and complete exercises provided in the notebooks.
Here’s a concise version for the README:

### Method 2: Open Directly in Google Colab

To open notebooks directly from GitHub in Google Colab:

1. Open [Google Colab](https://colab.research.google.com/).
2. Go to **File > Open Notebook**.
3. Select the **GitHub** tab.
4. Paste the GitHub URL of the notebook (e.g., `https://github.com/egemenokte/Programming_for_Engineers/blob/main/P1_Python_Basics_Data_Types.ipynb`) and press Enter.
5. Click on the notebook name to open it in Colab.

Example:  
To open the **P1: Python Basics and Data Types** notebook, paste:  
`https://github.com/egemenokte/Programming_for_Engineers/blob/main/P1_Python_Basics_Data_Types.ipynb`

---
## Contributing

Contributions to enhance the materials or suggest improvements are welcome! Please submit a pull request or open an issue for discussion.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer
This resource was created for Fall 2024 semester. Large language models were used to help with the creation of this readme file.
