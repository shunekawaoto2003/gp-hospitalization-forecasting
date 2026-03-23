# Probabilistic Forecasting of County-Level COVID-19 Hospitalizations Using PM2.5 and Gaussian Processes

This repository contains the code and materials for my Master's thesis at California State University, Long Beach.

## Overview

This project develops a two-stage Gaussian process (GP) pipeline:

1. **PM2.5 Imputation**
   - Spatio-temporal GP used to fill missing air pollution data

2. **Hospitalization Forecasting**
   - GP regression using lagged hospitalization and pollutant features
   - Compared against AR(3) baseline

## Repository Structure

- `notebooks/` – Jupyter notebooks for analysis
- `src/` – Core Python functions and models
- `results/` – Figures and tables
- `thesis/` – Final thesis document

## Methods

- Gaussian Process Regression
- Matérn, RBF, ARD, and periodic kernels
- Log-marginal likelihood optimization
- Monte Carlo simulation for uncertainty

## Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
