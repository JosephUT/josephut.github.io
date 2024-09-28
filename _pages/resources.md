---
permalink: /resources/
title: "Resources"
author_profile: false
---

This page is dedicated to younger me. I mainly use this page to help me structure and metric my own understanding of robotics, but I also hope it can be useful for younger roboticists who are trying to flesh out their own mental models. I try to focus on a relatively small number of high quality resources, mostly full online courses, textbooks, technical books, or at least midlength reports or lecture series. In addition to links I try write down what I found a given resource most useful for, point out connections to other ideas or resources, and also provide some context for the sections I've used to organize things. 

There is always more to learn, so I apologize for all the holes.

# Robotics
<!-- Image here -->
These are roughly the full set of problems robotic systems need to address. In particular applications, some of the problems do not have to be addressed at all. I keep sections for the problems I'm most concerned with below, but the boundaries between sections should be viewed as blurry (or nonexistant).

## Estimation

probabilistic robotics
state estimation for robotics

## SLAM

## Perception

## Task Planning

## Motion Planning

## Control

# Computation
<!-- Image here -->
These are areas of computing that are most relevant for work on the robot.

## Algorithms, Computability, and Complexity

## Software Engineering

## Middleware and System Programming

## Embedded Linux, Networking, and Drivers

## ML Frontends, ML Compilers, and GPU Programming

# Theory
<!-- Image here -->
These are the main topics I've found helpful to study on their own. Generally, deep learning addresses problems closer to AI while control theory addresses problems closer to the physical system, but robotics is a beautiful field in large part because the two bleed into each other in the middle. Optimization is a workhorse across the board. It's behind some of the best methods in estimation, localization, planning, and control. It can also solve reasoning problems, provided they are well defined. Besides optimization, there are several numerical methods (matrix methods, numerical integrators) and fields of math (probability theory, dynamical systems theory) that are relevant to the roboticist. Mostly, however, I think they become relevant by what they contribute to one of the three below.

## Artificial Intelligence

### Machine Learning

### Probabilistic and Graphical Models

### Game Theory

## Control Theory

### Linear Control

### Geometric Control

### Nonlinear Control

### Optimal Control

### Robust Control

### Adaptive Control

## Optimization and Numerical Methods

### Convex Optimization
- Least Squares
- Linear Programming
- Quadratic Programming
- Second Order Cone Programming
- Semidefinite Programming

### Nonconvex Optimization
- Zero order methods - Bayesian Optimization
- First order methods - Gradient Descent
- Quasi-Newton methods - Gauss-Newton, Levenberg Marquardt
- Second order methods - Netwon methods
- Trust region methods
- Line search methods

- Optimization on Manifolds

### Discrete Optimization
- Mixed Integer Programming
- Constraint Programming
- Boolean Satisfiability
- Satisfiability Modulo Theories

### Numerical Methods
- Matrix Factorizations
- Numerical Integrators

- Symbolic Algebra and Differentiation

## Math
- Linear Algebra
- Probability Theory
- Dynamical Systems Theory
- Differential Geometry
- Topology
- Group Theory
- Abstract Algebra
- Theory of Computation
- Real Analysis