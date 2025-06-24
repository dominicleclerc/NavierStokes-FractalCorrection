# NavierStokes-FractalCorrection

This repository contains the simulation code, energy analysis, and spectral tools associated with the article:

**"Global Regularity of the 3D Incompressible Navier–Stokes Equations via a Spectral Fractal Correction"**  
Author: Dominic Leclerc  
Laboratory of Mathematics and Theoretical Physics, Cosmologix Inc. (Rawdon, QC, Canada)  
Date: June 2025

---

## 📄 Overview

This work proposes a spectral fractal correction applied to the 3D incompressible Navier–Stokes equations.  
The correction acts as a nonlocal, scale-adaptive damping operator to ensure global smoothness of the velocity field.  
All simulations were performed in 2D using a pseudo-spectral method.

---

## 📁 Repository Contents

- `simulate.py` — main 2D pseudo-spectral simulation with fractal damping
- `plot_energy.py` — plots the kinetic energy evolution over time
- `plot_spectrum.py` — computes and displays the angularly averaged energy spectrum
- `energy.npy`, `u_final.npy`, `v_final.npy` — data saved during simulation
- `figure2_energy_spectrum.png`, `figure3_energy_evolution.png` — generated plots
- `requirements.txt` — list of required Python packages

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python simulate.py
python plot_energy.py
python plot_spectrum.py

