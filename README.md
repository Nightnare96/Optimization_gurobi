

# Operations Research Problems using Gurobi (Python)

This repository contains a collection of **Operations Research (OR) optimization problems** implemented using Gurobi in Python.

It includes a wide range of classical models such as **Linear Programming (LP), Integer Programming (IP), Quadratic Programming (QP), and Network Optimization problems**, making it useful for **learning, practice, and interview preparation**.



##  Features

* ✔️ 17+ Optimization Problems implemented
* ✔️ Covers LP, MIP, QP, Network Flow, Scheduling, and Game Theory
* ✔️ Clean and structured Python implementation
* ✔️ Includes optimal solutions for each problem
* ✔️ Beginner-friendly and interview-focused



##  Problem List

| No. | Problem                          |
| --- | -------------------------------- |
| 1️ | Two Variable Maximization (LP)   |
| 2️ | Resource Allocation (LP)         |
| 3️ | Cost Minimization                |
| 4️ | Knapsack Problem (Binary IP)     |
| 5️ | Quadratic Optimization           |
| 6️ | Assignment Problem               |
| 7️ | Transportation Problem           |
| 8️ | Nonlinear Constraints            |
| 9️ | Facility Location / Selection    |
| 10  | Diet Problem                     |
| 11  | Capital Budgeting (MIP)          |
| 12  | Production Planning (Integer LP) |
| 13  | Shortest Path (Network Model)    |
| 14  | Shift Scheduling                 |
| 15  | Shadow Price Analysis            |
| 16  | Multi-period Lot Sizing          |
| 17  | Game Theory (Zero-Sum Game)      |



## Installation

Install Gurobi Python package:

```bash
pip install gurobipy
```

Then activate your Gurobi license (Academic license is free).



## Usage

Run the Python file:

```bash
python your_file_name.py
```

Each function solves a specific optimization problem and prints:

* Optimal Objective Value
* Decision Variable Values


## Example

### Two Variable Linear Programming Problem

**Maximize:**

```
Z = 5x + 4y
```

**Subject to:**

```
6x + 4y ≤ 24  
x + 2y ≤ 6  
x, y ≥ 0  
```

**Optimal Solution:**

```
Z = 21  
x = 3  
y = 1.5  
```


##  Key Learning Outcomes

* Formulating real-world problems into mathematical models
* Understanding constraints and objective functions
* Solving LP, MIP, and QP using Python
* Using Gurobi for optimization
* Interpreting optimal solutions and dual values


##  Tech Stack

* Python
* Gurobi Optimizer
* Mathematical Optimization


##  Applications

* Supply Chain Optimization
* Logistics & Transportation
* Production Planning
* Workforce Scheduling
* Finance & Investment Decisions
* Network Optimization



##  Future Improvements

* Add visualization of solutions
* Include real-world datasets
* Extend to stochastic optimization
* Integrate with Pyomo / OR-Tools
