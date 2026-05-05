# Trajectory-Dependent-Irreversibility-in-Conserved-Phase-Field-Dynamics
This repository contains all simulation code, data, and figure-generation scripts supporting the results presented in the associated research paper.  The study introduces an entropy-indexed irreversibility measure to quantify trajectory-dependent microstructural evolution in conserved systems governed by phase-field dynamics.

Author: Pranshu Bharadwaj
Year: 2026

Description:
This script implements numerical simulations of conserved phase-field dynamics
based on the Cahn–Hilliard equation. It reproduces all experiments presented
in the associated research paper, including:

A. Deterministic evolution
B. Path dependence under identical constraints
C. Stochastic perturbations
D. Mobility variation
E. Thermodynamic parameter sweep (A)
F. Independence from energy and structure

Outputs:
- Free energy evolution F(t)
- Structure factor S(k,t)
- Entropy S(t)
- Irreversibility measure I(t)

Reproducibility:
All parameters, initial conditions, and random seeds are fixed where required.

License:
MIT License
"""
