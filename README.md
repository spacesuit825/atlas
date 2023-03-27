# ATLAS GPU Finite Element Modelling (sub-project of AURORA)

Atlas is an optimised finite element solver, designed to take advantage of the GPU. The project aims to produce FEM results for massive (linear or non-linear) solves (ie. tens to hundreds of millions of nodes) in realtime (or near-realtime).

This project will hopefully support:
- An optimised GPU-accelerated pipeline for mesh generation and solving in realtime using a hybrid CPU-GPU approach
- Support of common non-linearities, including contacts, large displacements and custom material models
- Simple standalone GUI with some tools for realtime interaction
- Directly compatible (and coupled) with the rest of Aurora's physics solvers (MPM, LBM, SPH, rigid bodies, XPBD)

TODO:
- Finalise the solver pipeline architecture
