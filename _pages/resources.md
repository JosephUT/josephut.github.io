---
permalink: /resources/
title: "Resources"
author_profile: false
---

This is where I keep links to resources I've found useful while studying robotics. I try to focus on a relatively small number of high quality resources, mostly full online courses, textbooks, technical books, or at least midlength reports or lecture series. I also use this page to help me structure and metric my own understanding. In addition to links I try write down what I found a given resource most useful for, point out connections to other ideas or resources, and also provide some context for the sections I've used to organize things.

This is and likely will always be a work in progress, so I apologize for all the holes and disorganization.

# Robotics

## Filtering and Estimation

## SLAM

## Perception

## Task Specification and Human Robot Interaction

## AI and Task Planning

## Motion Planning

## Control

# Computation

## Software Engineering

## Middleware and Embedded Linux

## FPGA Acceleration and High Performance Networking

## GPU Acceleration and Model Inference Optimization

# Theory

## Deep Learning

## Control Theory

## Math


- How does this help me solve problems?
- How can I leverage computing for this kind of problem?

### Tools for Getting the Answer
I think of these items as the main mathematical work horses that actually give me answers and get me numbers. Generally this is applied math, although some of the tools here are pretty basic, like solving linear equations. There are a lot of valuable computational tools here since these are mostly methods that involve computation.

- Matrix Factorizations
- Numerical Integrators
- Symbolic Algebra and Differentiation

- Convex Programming
    - Least Squares
    - Linear Programming
    - Quadratic Programming
    - Second Order Cone Programming
    - Semidefinite Programming
- Nonconvex Programming
    - Zero order methods - Bayesian Optimization
    - First order methods - Gradient Descent
    - Quasi-Newton methods - Gauss-Newton, Levenberg Marquardt
    - Second order methods - Netwon methods
    - Trust region methods
    - Line search methods
- Mixed Integer Programming
- Constraint Programming
- Boolean Satisfiability
- Satisfiability Modulo Theories

### Tools for Understanding the Structure
I think of these items as helping me understand and model problems rather than actually solve them.

- Linear Algebra
- Probability Theory
- Dynamical Systems Theory
- Differential Geometry
- Topology
- Group Theory
- Abstract Algebra
- Theory of Computation

### Tools for Proving Things
I don't find that I have to prove things very often. I typically just use theory and methodology that mathematicians have already worked out. One key exception is proving properties of a control system so that I know it will work. This generally leans on real analysis if you go back far enough. Another exception is proving that a mathematical program is convex such that I know a convex programming method will be able to solve it to global optimality.

- Logic and Natural Deduction
- SMT Solvers
- Real Analysis

should probably move these up two sections.