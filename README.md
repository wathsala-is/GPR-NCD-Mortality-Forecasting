# GPR NCD Mortality Forecasting

This repository contains the reproducibility materials for the manuscript
"Forecasting Noncommunicable Disease Mortality Using Gaussian Process
Regression: A Non-parametric Machine Learning Approach".

## Main analysis notebooks

- GPModels_NCDData_Revised_26.09.ipynb
  - mortality-data preparation
  - primary temporal hold-out validation
  - rolling-origin sensitivity analysis
  - final 2000-2019 model fitting
  - 2020-2030 forecasting
  - manuscript figures and tables
  - convergence diagnostics

- GPKernels_Revised_26.09.ipynb
  - kernel and covariance figures

## Input datasets

- NoD_to_NCD.csv
- Population_Total.csv
- Population_Female.csv
- Population_Male.csv

## Reproduction

Run GPModels_NCDData_Revised.ipynb from a fresh kernel
in cell order with the four CSV input files available in the
working directory.

The analysis uses WHO mortality data for 2000-2019 and
World Bank total and sex-specific population denominators.
