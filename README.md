# Final Project: Electrodynamics 
## BUAP - FCFM

# Propagación de Ondas Electromagnéticas en Medios Dieléctricos

**Proyecto Final de Electrodinámica**

## Description

This project studies the propagation of electromagnetic waves in symmetric three-layer dielectric waveguides. A numerical analysis is implemented to determine the allowed TE (Transverse Electric) guided modes in a dielectric structure with core and cladding.

## Team

- Valeria López Agustín
- Celso Rojas Pérez
- Mariana Martínez Cupul

## Contents

1. **Derivation of the vector wave equation** in linear, isotropic, and homogeneous media from Maxwell’s equations
2. **Validation of monochromatic plane waves** as solutions of the wave equation
3. **TE polarization relations** (Ey, Hx) in waveguides
4. **Configuration analysis** of a GaAs/AlGaAs (3-layer) waveguide
5. **Boundary conditions** at dielectric interfaces
6. Numerical solution of the transcendental **characteristic equation** for guided modeS
7. Visualization of **electric field distributions** for multiple modess

## Waveguide Parameters

- **Material:** GaAs/AlGaAs
- **Refractive index (core):** n₂ = 3.6
- **Refractive index (cladding):** n₁ = 3.3
- **Core thickness:** d = 2.0 μm
- **Wavelength:** λ = 0.87 μm
- **V-number::** V ≈ 10.39 (multimode)

## Modes Found

The analysis identifies **4 guided TE modes** propagating in the structure, with TE₀ being the fundamental mode with the highest propagation constant 
β.

## Requirements

```python
numpy
matplotlib
scipy.optimize.brentq
```

## How to run

```bash
jupyter notebook FinalProject_Electrodynamics-1.ipynb
```

## Notes

The project implements root-finding to solve transcendental characteristic equations for even (symmetric) and odd (antisymmetric) modes, including the calculation of derived parameters such as the (β) and effective index (neff). 
