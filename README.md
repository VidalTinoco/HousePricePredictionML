# Predictive Modeling of House Prices

## Overview

This repository contains the final report and associated scripts for a house price prediction project using advanced regression techniques. We analyze and compare models (linear, tree-based, and generalized) on the Kaggle dataset "House Prices - Advanced Regression Techniques" to understand feature importance, price distribution, and non-linear relationships.

## Key Dependencies

* numpy
* pandas
* scikit-learn
* statsmodels
* matplotlib
* seaborn
* jupyter

## Main Findings

* The Gradient Boosting model achieved the lowest RMSE (\~26,717) and R² ≈ 0.91.
* Log-normal transformation best fits sale prices according to AIC/BIC.
* LASSO highlighted `OverallQual`, `GrLivArea`, and `GarageCars` as top predictors.
* Advanced models capture non-linear relationships better than simple linear regression.
* Temporal (year built, remodel year) and spatial effects (neighborhood) significantly influence price.

---

*For full details, see the project report in `Report.pdf`.*
