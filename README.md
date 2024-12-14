# Bumblebee Habitat Range Shift Analysis

## Overview
This repository contains supplemental materials for the analysis of how temperature variation due to climate change has affected the migration pattern of bumblebee species in North America over the past century.

## File Descriptions
1. **Bumblebee_EDA.Rmd**: Exploratory Data Analysis (EDA) of the bumblebee habitat data, including visualization and descriptive statistics.
2. **Permutation+Monte_Simulation.Rmd**: Details the permutation tests and Monte Carlo simulations used to validate model assumptions.
3. **MCMC.Rmd**: Markov Chain Monte Carlo (MCMC) simulations used for Bayesian inference in the study.
4. **Permutation_Model.Rmd**: Implements the permutation model for statistical testing.
5. **Monte_Modeling_Data.Rmd**: Analysis of temperature and habitat modeling using Monte Carlo methods.
6. **final_data_1.csv**: The cleaned dataset used for the analyses, with detailed variables explained below.

## Dataset
**final_data_1.csv**
- `species`: Bumblebee species.
- `kmNorthEquator`: kmNorthEquator of bumblebee habitat.
- `elevation`: elevation of bumblebee habitat.
- `maxPeriodAnnualMeanT`: Annual maximum temperatures.
- `minPeriodAnnualMeanT`: Annual minimum temperatures.
- `meanTemp`: The average temperature during the observed period.
- `periodFrom` and `periodTo`: Time interval.
