# Fourier Optics: Mathematical Analysis, Simulation, and Diffraction

[![Course](https://img.shields.io/badge/Course-Signals%20and%20Systems-blue)](https://github.com/HeliaTJB/Fourier-Optics)
[![University](https://img.shields.io/badge/University-Sharif%20University%20of%20Technology-red)](https://www.sharif.edu/)
[![Python](https://img.shields.io/badge/Python-3.x-yellow?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)

## Overview

This project studies **Fourier Optics** from both mathematical and computational perspectives. The main goal was to understand how the Fourier-transform representation of optical fields connects the mathematical description of diffraction with observable optical patterns.

The project was developed in two phases:

1. **Theoretical foundations** — mathematical analysis of the two-dimensional Fourier transform and diffraction approximations.
2. **Diffraction analysis and simulation** — applying the developed theory to different optical apertures, reproducing diffraction patterns numerically, and comparing the simulations with the analytical results.

The project combines concepts from **Fourier analysis, signal processing, mathematical modeling, and computational simulation**.

---

## Project Structure

| Phase                  | Focus                           | Main Methods                                                                       |
| ---------------------- | ------------------------------- | ---------------------------------------------------------------------------------- |
| **Phase 1**            | Mathematical foundations        | 2D Fourier Transform, Fourier-domain analysis, Fresnel & Fraunhofer approximations |
| **Phase 2**            | Diffraction and optical systems | Analytical derivation, numerical simulation, aperture analysis, coherence          |
| **Computational Work** | Numerical verification          | Python, NumPy, Matplotlib, Jupyter Notebook                                        |

---

## Phase 1 — Mathematical Foundations

The first phase establishes the mathematical framework required for Fourier-optics analysis.

### 1. Two-Dimensional Fourier Transform

We studied the two-dimensional Fourier transform and its properties as a mathematical representation of spatial signals.

Particular attention was given to understanding how spatial-domain structures are represented in the frequency domain and how Fourier-domain analysis can be used to study optical propagation and diffraction.

This provides the mathematical connection between **spatial signals** and their **frequency-domain representations**.

### 2. Diffraction Approximations

We then studied two important approximations used in diffraction analysis:

* **Fresnel diffraction**
* **Fraunhofer diffraction**

The approximations were derived and examined in terms of their mathematical assumptions and regimes of applicability.

The purpose of this phase was not only to obtain the final formulas, but to understand how the approximations arise from the underlying mathematical description of wave propagation.

---

## Phase 2 — Diffraction from Optical Apertures

In the second phase, the theoretical framework developed in Phase 1 was applied to several optical aperture configurations.

For each aperture, the diffraction pattern was investigated in two complementary ways:

1. **Analytical analysis** — deriving the expected diffraction behavior from the mathematical model.
2. **Numerical simulation** — implementing the corresponding calculations in Python and visualizing the resulting optical patterns.

The numerical results were then compared with the analytical predictions to examine the consistency between the mathematical model and the computational implementation.

### Aperture Analysis

The simulations investigate how the geometry of an aperture affects the resulting diffraction pattern.

This provides a practical example of how a spatial-domain structure can determine a characteristic frequency-domain or far-field pattern through the Fourier-transform relationship.

---

## Coherent and Incoherent Imaging

The project also examines the distinction between **coherent and incoherent light** and how coherence influences the resulting optical patterns.

This part extends the analysis from individual diffraction patterns toward the behavior of optical imaging systems, providing a connection between Fourier-domain representations and image formation.

---

## Computational Implementation

The numerical experiments were implemented using Python and Jupyter Notebook.

The computational workflow follows the mathematical development:

```text
Optical Aperture
       ↓
Mathematical Model
       ↓
Fourier-Domain Representation
       ↓
Diffraction Calculation
       ↓
Numerical Simulation
       ↓
Visualization
       ↓
Comparison with Analytical Results
```

The main computational tools include:

* **Python**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

The notebook `simulations.ipynb` contains the main numerical experiments and visualizations.

---

## Repository Contents

```text
Fourier-Optics/
│
├── Figures/
│   └── Generated figures and visual results
│
├── P13_Pics/
│   └── Project-related images
│
├── simulations.ipynb
│   └── Numerical simulations and visualizations
│
├── phase1.pdf
│   └── Phase 1 report
│
├── phase1_FullReport.pdf
│   └── Extended Phase 1 report
│
├── phase2.pdf
│   └── Phase 2 report
│
└── README.md
```

---

## Key Concepts

The project covers the following topics:

* Two-dimensional Fourier Transform
* Spatial and frequency-domain representations
* Fourier analysis of optical fields
* Fresnel diffraction
* Fraunhofer diffraction
* Optical apertures
* Diffraction patterns
* Coherent and incoherent light
* Numerical simulation
* Computational visualization
* Mathematical and numerical comparison

---

## What This Project Demonstrates

This project provided practical experience in connecting mathematical theory with computational experiments.

In particular, it involved:

* translating mathematical models into numerical simulations;
* using Fourier-transform methods to analyze spatial phenomena;
* deriving and interpreting diffraction behavior;
* validating analytical expectations through computation;
* visualizing two-dimensional numerical results;
* connecting signal-processing concepts with optical imaging.

A central aspect of the project was maintaining a direct connection between the **mathematical formulation**, its **computational implementation**, and the resulting **physical interpretation**.

---

## References

The theoretical development was based on standard Fourier-optics and signal-processing concepts, with particular emphasis on the mathematical treatment of Fourier transforms and diffraction.

Recommended references for further study include:

* J. W. Goodman, *Introduction to Fourier Optics*.
* Standard references on Fourier analysis and linear systems.
* Course materials for **Signals and Systems**, Sharif University of Technology.

---

## Authors

**Helia Tajabadi**
[GitHub](https://github.com/HeliaTJB)

**AmirAli Jahanbakhshi**
[GitHub](https://github.com/AmirAli-jb)

**Signals and Systems — Sharif University of Technology**

Instructor: **Dr. Dastgheib**
