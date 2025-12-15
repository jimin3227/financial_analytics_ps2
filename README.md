# financial_analytics_ps2
Asset Pricing with PCA Factors and Fama–MacBeth Regressions

# Asset Pricing with PCA Factors and Fama–MacBeth Regressions

This repository contains code and analysis for an empirical asset pricing exercise
using the 25 Size–Book-to-Market portfolios from the Fama–French data library.

## Overview
The project focuses on constructing risk factors and evaluating asset pricing models
using cross-sectional tests.

Main components include:
- Construction of principal component (PCA) factors from portfolio excess returns
- In-sample vs. out-of-sample PCA factor comparison
- Fama–MacBeth-style cross-sectional regressions
- Comparison with Fama–French and macroeconomic factor models

## Data
- 25 Size × BE/ME portfolios (monthly returns)
- Fama–French factors (MKT, SMB, HML, RF)
- Macroeconomic variables (dividend yield, default spread, term spread)

## Methods
- Covariance matrix estimation and eigen-decomposition
- Factor construction via principal components
- Cross-sectional asset pricing regressions
- Model performance comparison using γ estimates and R²

## Purpose
This repository is intended for academic use and reproducibility,
with an emphasis on clear implementation of empirical asset pricing techniques.