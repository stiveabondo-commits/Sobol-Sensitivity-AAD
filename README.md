# Recursive Global Sensitivity Analysis (Sobol Indices)

High-dimensional sensitivity analysis using modern stochastic optimization techniques and Adjoint Algorithmic Differentiation (AAD).

##  Objective
Estimate Sobol indices in highly constrained environments ($d=50$) while avoiding the curse of dimensionality, applying methodologies crucial for quantitative risk management.

##  Key Features
- **Online Pick-Freeze Mirror Descent:** Algorithm design for continuous parameter learning.
- **Adjoint Algorithmic Differentiation (AAD):** Implemented via PyTorch to compute "Cheap Gradients" with $O(1)$ complexity.
- **Auto-Targeting Strategy:** Noise filtration to isolate critical risk factors in non-linear systems.

##  Technologies
`Python`, `PyTorch`, `NumPy`, `Stochastic Calculus`, `Risk Modeling`
