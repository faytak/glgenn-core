# Generalized Lipschitz Group Equivariant Neural Networks (GLGENN)

## Overview
This repository contains implementation of Generalized Lipschitz Group Equivariant Neural Networks (GLGENN). These networks are equivariant to any pseudo-orthogonal transformation of a $n$-dimensional real vector space. The architecture of GLGENN contains
* ${C \kern -0.1em \ell}^{\overline{k}}$-linear layers,
* ${C \kern -0.1em \ell}^{\overline{k}}$-geometric product layers,
* ${C \kern -0.1em \ell}^{\overline{k}}$-normalization layers,

GLGENN generalize Clifford Group Equivariant Neural Networks (CGENN).


## Code Organization
* `algebra/`: Contains implementation of quaternion types subspaces in Clifford algebra.
* `data/`: Contains data loading scripts for experiments.
* `engineer/`: Contains training, evaluation, and visualization scripts.
* `experiments/`: Contains experimental results.
* `layers/`: Contains architecture of GLGENN layers.
* `models/`: Contains models built from GLGENN layers.

## Experiments
GLGENN demonstrates enhanced performance on benchmark equivariant tasks, including equivariant regression task and convex hull volume estimation,  outperforming state-of-the-art models in several setups with fewer parameters, and demonstrating less tendency to overfitting. The setups and results of $\mathrm{O}(5,0)$-Equivariant Convex Hull Experiment and Regression Task Experiment are presented in `experiments/`.