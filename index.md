---
layout: default
---

## Optimal control software framework

### [Open Optimal Control Library](https://openocl.org) (Matlab/Octave)

The Open Optimal Control Library is a toolbox for Matlab/Octave that facilitates modelling and formulation of (parametric) optimal control problems. It interfaces Ipopt [1] to numerically solve the optimal control problems and CasADi [2] to automatically calcuate the necessary derivatives by algorithmic differentiation.

### [ACADO Toolkit](http://acado.github.io/) (C++, Matlab)

ACADO Toolkit is a software environment and algorithm collection for automatic control and dynamic optimization. It provides a general framework for using a great variety of algorithms for direct optimal control, including model predictive control, state and parameter estimation and robust optimization. ACADO Toolkit is implemented as self-contained C++ code and comes along with user-friendly MATLAB interface. The object-oriented design allows for convenient coupling of existing optimization packages and for extending it with user-written optimization routines.

### [CasADi](http://casadi.org/) (C++, Python, Matlab/Octave)

CasADi is an open-source tool for nonlinear optimization and algorithmic differentiation. It facilitates rapid — yet efficient — implementation of different methods for numerical optimal control, both in an offline context and for nonlinear model predictive control (NMPC).

Paper Abstract [2]
: We present CasADi, an open-source software framework for numerical
optimization. CasADi is a general-purpose tool that can be used to model and solve
optimization problems with a large degree of flexibility, larger than what is associated
with popular algebraic modeling languages such as AMPL, GAMS, JuMP or Pyomo.
Of special interest are problems constrained by differential equations, i.e. optimal
control problems. CasADi is written in self-contained C++, but is most conveniently
used via full-featured interfaces to Python, MATLAB or Octave. Since its inception
in late 2009, it has been used successfully for academic teaching as well as in applications from multiple fields, including process control, robotics and aerospace. This
article gives an up-to-date and accessible introduction to the CasADi framework,
which has undergone numerous design improvements over the last seven years.

### [Ipopt](https://projects.coin-or.org/Ipopt) (C++, multiple interfaces)

Ipopt is a software package for large-scale nonlinear optimization. It is designed to find (local) solutions of mathematical optimization problems. IPOPT has been designed to be flexible for a wide variety of applications, and there are a number of ways to interface with IPOPT that allow specific data structures and linear solver techniques. The list of interfaces includes AMPL, C++, C, Fortran, Java, R, Matlab, Julia. 

Paper Abstract [1]
: We present a primal-dual interior-point algorithm with a filter line-search method for nonlinear
programming. Local and global convergence properties of this method were analyzed in previous work. Here
we provide a comprehensive description of the algorithm, including the feasibility restoration phase for the filter method, second-order corrections, and inertia correction of the KKT matrix. Heuristics are also considered
that allow faster performance. This method has been implemented in the IPOPT code, which we demonstrate
in a detailed numerical study based on 954 problems from the CUTEr test set. An evaluation is made of several
line-search options, and a comparison is provided with two state-of-the-art interior-point codes for nonlinear
programming.

## References

[1] On the Implementation of a Primal-Dual Interior Point Filter Line Search Algorithm for Large-Scale Nonlinear Programming  
A. Wächter, L.T. Biegler  
Mathematical Programming 106 (2006) 25-57, Available at: [projects.coin-or.org/Ipopt](https://projects.coin-or.org/Ipopt)

[2] CasADi - A software framework for nonlinear optimization and optimal control  
J.A.E. Andersson, J. Gillis, G. Horn, J.B. Rawlings, M. Diehl  
Mathematical Programming Computation, In Press, 2018, Available at: [casadi.org](http://casadi.org)

## Contact

info [at] optimal-control.org
