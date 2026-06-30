# V9-Inventory-Cosmology
Inventory-driven dynamical vacuum cosmology with native CLASS implementation and MCMC constraints from Planck 2018, BAO, and Pantheon+.
# V9 Inventory Cosmology

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-blue)
![Cosmology-V9-orange](https://img.shields.io/badge/cosmology-V9-orange)

An inventory-driven dynamical vacuum cosmology based on closure inventory growth.

## Overview

This repository contains the native CLASS implementation, MCMC analysis scripts, and supporting material for the V9 inventory cosmology framework.

The model introduces a dynamical vacuum energy component governed by the growth of a closure inventory:

`ρΛ(a) ∝ I(a)^(-1)`

rather than by a fundamental scalar field.

The present implementation is restricted to post-inflationary cosmology.

---

## Main Features

- Native implementation in CLASS v3.3.4
- Inventory-driven vacuum depletion
- Planck 2018 + BAO + Pantheon+ MCMC constraints
- Matched $\Lambda$CDM comparison
- Higher inferred $H_0$
- Lower inferred $S_8$

---

## Current Results

| Parameter | LCDM | V9 |
|-----------|------|------|
| Best-fit χ² | 4142.99 | 4140.92 |
| H0 [km/s/Mpc] | 67.94 | 71.36 |
| Ωm | 0.308 | 0.279 |
| S8 | 0.822 | 0.791 |

---

## Repository Structure

```text
paper/           Manuscript PDF and LaTeX source
class_patch/     Modified CLASS source files
mcmc/            Cobaya configuration files
results/         MCMC summaries and figures
scripts/         Analysis scripts
```

---

## Status

This project is currently under active development.

Future work includes:

- fully gauge-invariant inventory perturbations
- SH0ES likelihood analyses
- CMB lensing constraints
- ACT/SPT datasets
- primordial inventory dynamics

---

## Citation

If you use this repository, please cite the accompanying Zenodo record.

---

## Author

Sung-ho Ahn  
Independent Researcher

---

## Acknowledgements

The author acknowledges the use of ChatGPT (OpenAI) for discussions, analysis, coding assistance, and manuscript preparation.
