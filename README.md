# TCG-COSMOLOGY-H0-S8

## Constitutive Gravity (TCG V3) Cosmological Validation

This repository contains the numerical code and parameter inference results (MCMC chains) supporting the paper: "Cosmological Viability of Constitutive Gravity: Resolving the Hubble Tension and Large-Scale Structure without Dark Matter."

TCG V3 is a causal scalar-tensor extension of General Relativity designed to address non-Newtonian dynamics without invoking non-baryonic Dark Matter.

### Key Results

* **Dark Matter Replacement:** The DBI scalar field perturbation ($\delta\phi$) successfully replaces the kinetic and gravitational role of Cold Dark Matter, reproducing the CMB acoustic peaks and the Linear Matter Power Spectrum $P(k)$.
* **Hubble Tension Resolved:** The model's best fit yields $H_0 = 72.1 \pm 1.2$ km s$^{-1}$ Mpc$^{-1}$, reconciling the discrepancy between early-universe (CMB) and late-time (local supernova) measurements.
* **$S_8$ Tension Alleviated:** The intrinsic high pressure ($\csdos \ge 1$) of the DBI field introduces a natural cutoff, leading to a suppressed $\sigma_8 = 0.790 \pm 0.012$, which aligns better with weak lensing constraints.

### Code and Data

The core of this project is a modified version of the standard Boltzmann solver (TCG-CAMB), used to solve the coupled linear perturbation equations (see Supplemental Material).

* `/code/`: Modified TCG-CAMB source files (Fortran/C).
* `/mcmc/`: Full MCMC chains, convergence statistics, and likelihood files (using \texttt{GetDist}).
* `/results/figures/`: Primary figures (CMB spectrum, $P(k)$, Triangle Plot).

### Author and Contact

**Dr. Manuel Martín Morales Plaza (PhD)**\\
Independent Researcher, Canary Islands, Spain\\
Email: manuelmartin@doctor.com
