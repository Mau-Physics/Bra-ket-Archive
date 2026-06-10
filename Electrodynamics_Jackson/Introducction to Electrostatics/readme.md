# 1. INTRODUCTION TO ELECTROSTATICS - Classical Electrodynamics (J.D. Jackson)

This folder contains exhaustive solutions and high-fidelity boundary-value numerical simulations for Chapter 1 of John David Jackson's *Classical Electrodynamics*.

> [!IMPORTANT]
> **PDF Preview Issue:** Due to the extreme density of partial differential equations, multi-panel vector fields, and custom analytical footnotes, the GitHub web viewer may fail to render the preview. For the full experience, please **download the file** or clone the repository.

## 📄 Contents
*   **[Classical_Electrodynamics_Jackson_Sol_Ch1.pdf](./Electrodynamics_Jackson_Sol.1_INTRODUCTION_TO_ELECTROSTATICS.pdf):** 77 pages of rigorous LaTeX solutions structured as peer-reviewed short communications, utilizing advanced theoretical frameworks (Maxwell Stress Tensors, Legendre Transform Co-energies) to bridge electrostatics with fields and thermodynamics [Anterior, Anterior].
*   **[Braket_Jackson_1_Simulations.ipynb](./BraKet_Jakson_simulation_1_INTRODUCTION_TO_ELECTROSTATICS.ipynb):** High-performance Python notebook featuring customized Google Colab integration [`Colablink`](https://colab.research.google.com/drive/1polGb4yRlte0YBiZtCJ2ESrzPt5qagSB?usp=sharing), running Successive Over-Relaxation (SOR) matrix solvers optimized under eightfold symmetry masks [Anterior, Anterior].

## 🎯 Key Concepts & Interactive Simulations

The following highlights feature complete numerical implementations, boundary constraints, and visual assets demonstrating core electrostatic kinematics:

**Problem 1.4 - Gauss's Law Across Spherical Varieties**<br>Comparative computational physics laboratory solving the radial electric field $|E|$ for four distinct matter densities under strict Dirichlet boundary conditions ($a=1.0$) [Anterior]. Validates asymptotic global flux convergence [Anterior].
<img src="./gifs/gauss_law_spherical_varieties.gif" alt="Gauss Law Spherical Varieties"/>

**Problem 1.5 - The Quantum-Classical Hydrogen Atom**<br>Continuous Poisson solver tracking the electronic screening progress factor. Illustrates the geometric interplay between the discrete proton singularity ($\delta$-function nucleus) and the continuous exponential $1s$ orbital charge density [Anterior].
<img src="./gifs/hydrogen_screening_progress.gif" alt="Hydrogen Screening Simulation"/>

**Problem 1.9 - Actuator Pull-In Instability (MEMS Mode)**<br>Dynamic electromechanical coupling simulation tracking the competition between Hooke's linear spring force and the non-linear electrostatic attraction ($\propto 1/x^2$) [Anterior]. Captures the exact micro-second transient collapse under voltage-control [Anterior].
<img src="./gifs/mems_pull_in_instability.gif" alt="MEMS Pull-In Simulation"/>

**Problem 1.11 - Electrostatic Boundary Flux & Surface Curvature**<br>Geometric differential solver animating a mutating conductor interface to confirm the invariant coupling between the normal derivative of the field ($\frac{\partial E}{\partial n}$) and the local Mean Curvature ($2H = \frac{1}{R_1} + \frac{1}{R_2}$) along the diagonal $Y=X$ line [Anterior, Anterior].
<img src="./gifs/curvature_differential_solver.gif" alt="Surface Curvature Simulation"/>

**Problem 1.23 & 1.24 - 2D Transmission Line Lattice Relaxation (SOR)**<br>High-fidelity numerical field solver executing **5,185 Successive Over-Relaxation iterations** ($\omega = 1.75$) over an explicit eightfold symmetry mesh fraction [Anterior, Anterior]. Audits discretization errors down to a $\mathcal{O}(h^2)$ grid convergence limit with strict $10^{-10}$ floating-point precision [Anterior, Anterior].
<img src="./gifs/transmission_line_sor_3d_relaxation.gif" alt="SOR 3D Potential Surface Relaxation"/>

---
*Part of the [Bra-ket Archive](https://github.com) project for PhD preparation.*

## 🎥 Video Explanations
Detailed walkthroughs and masterclasses for these theoretical and numerical deep dives:
1.  [**Jackson 1.4 - Generalizing Gauss's Law to Radical Densities**](YOUR_LINK_1)
2.  [**Jackson 1.9 - Thermodynamics of MEMS: Co-Energy & Pull-In Limits**](YOUR_LINK_2)
3.  [**Jackson 1.11 - Differential Geometry Applied to Conducting Fields**](YOUR_LINK_3)
4.  [**Jackson 1.13 - Green's Reciprocity vs. Infinite Image Series**](YOUR_LINK_4)
5.  [**Jackson 1.23 - Coding SOR & Relaxation Algorithms from Scratch**](YOUR_LINK_5)

---
*Follow the journey to Cambridge PhD at [Bra-Ket Archive](https://youtube.com)*
