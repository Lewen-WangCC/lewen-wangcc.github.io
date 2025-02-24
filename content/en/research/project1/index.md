---
title: "Modelling Spin-Crossover Lattices with Machine-Learned Force Fields"
summary: Supervised by Prof. Ben Powell and Dr Carla Verdi
authors:
- admin
date: 2024-01-29
doi: ""

abstract: Machine learning force fields (MLFF) have received increasing attention recently due to their ability to describe interatomic potentials with quantum-level accuracy while scaling to classical systems. The accuracy of the machine-learned potentials highly depends on the choice of the underlying _ab initio_ reference method. However, modelling spin-crossover (SCO) lattices using density functional theory (DFT) still presents difficulties, especially in balancing accuracy and efficiency when predicting the energy difference between the high- and low-spin states at 0 K, known as the enthalpy difference. In this thesis, a semi-empirical DFT method was employed to train MLFFs for [Fe(ptz)~6~]\(BF~4~)~2~ (ptz = 1-propyltetrazole) on the fly during molecular dynamics (MD) simulations. The developed MLFFs achieved DFT-level accuracy with high efficiency across a series of benchmarks and successfully predicted the thermal expansion effect of the SCO system using quasi-harmonic approximations. This study provides key insight into modelling SCO with DFT, highlighting the critical role of zero-point effects in the enthalpy difference calculation. Combining a reliable DFT reference with MLFF provides a promising strategy for accurately and efficiently simulating the lattice dynamics of SCO systems. Additionally, a potential scheme for MLFF-driven MD simulations was proposed.

tags:
  - ML
  - AIMD
  - VASP
featured: false

url_pdf: thesis.pdf

image:
  caption: 'Image credit: Huiwen Tan'
  focal_point: ""
  preview_only: ture

projects: []

slides: ""
---