# Bayesian Homework: PyMC & Slice Sampling

This repository contains my Week 5 homework solutions for Bayesian inference using PyMC and slice sampling methods. The notebook is organized into three main parts:

- **Q1: PyMC Example Gallery Documentation**  
  A formatted Markdown listing of the contents of the "PyMC Example Gallery" with clickable titles and rendered images in a table format.

- **Q2: Bayesian Inference using PyMC**  
  Three different Bayesian models are implemented on synthetic normal data:
  1. **Model 1:** Normal prior for \(\theta\) and Gamma prior for \(\tau\).
  2. **Model 2:** Laplace prior for \(\theta\) (non-normal) and LogNormal prior for \(\tau\) (non-gamma).
  3. **Model 3:** Student-t prior for \(\theta\) (non-normal) and Exponential prior for \(\tau\) (non-gamma).

  Each model includes diagnostic assessments (trace plots, summary statistics, etc.) using ArviZ.

- **Q3: Slice Sampling within Gibbs**  
  A detailed explanation and code demonstration of the slice sampling algorithm, including how it can replace the Metropolis–Hastings step in a Metropolis‐within‐Gibbs sampler when full conditionals are known only up to a normalizing constant.

## Repository Structure

- **HW5 1.ipynb**: The Jupyter Notebook containing the full homework solution with markdown cells and code cells.
- **README.md**: This file.
