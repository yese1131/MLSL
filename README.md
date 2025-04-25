# Watermelon Market Modeling  
**CU Boulder: Introduction to Machine Learning – Supervised Learning Final Project**

## Overview

This project applies supervised machine learning techniques to a historical agricultural dataset from the 1930–1950s U.S. watermelon market. The goal is to predict **farm-level watermelon prices** using economic and environmental features such as population, freight costs, and surplus availability.

Through model diagnostics, multicollinearity analysis, and iterative refinement (including Cook’s Distance filtering), we developed a robust linear regression model with interpretable coefficients and high predictive power.

---

## Course Context

This repository is part of the course:  
[**Introduction to Machine Learning: Supervised Learning**](https://www.coursera.org/degrees/master-of-science-data-science-boulder)  
offered by the University of Colorado Boulder on Coursera.

In this course, we explore key supervised ML algorithms and when to use them:

- **Linear & Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Trees & Ensembles** (Random Forest, Boosting)
- **Support Vector Machines (SVM)**

We also build hands-on experience with essential Python tools:  
`NumPy`, `pandas`, `matplotlib`, `statsmodels`, and `scikit-learn`.

---

## What’s in this repo?

- `final.ipynb`: Jupyter notebook with:
  - Exploratory data analysis
  - Correlation & VIF diagnostics
  - Model building (baseline & extended)
  - Cook’s Distance influence filtering
  - Visualization of residuals and quadratic effects
- `watermelons.csv`: Cleaned historical watermelon dataset (log-transformed).
- `images/`: Saved figures (residual plots, partial regressions, Cook’s Distance)

---

## Key Learning Outcomes

- Practice selecting features and transforming variables for regression
- Learn to validate linear model assumptions using residuals, VIF, and partial plots
- Apply influence diagnostics to improve robustness (e.g. Cook’s Distance)
- Visualize and interpret model behavior in economic terms

---

## Requirements

- Python ≥ 3.8  
- Dependencies:  
  `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`

Install dependencies with:

```bash
pip install -r requirements.txt
