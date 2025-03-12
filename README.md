# HW7
# Homework 7 Solutions

This repository contains my solutions for Homework 7. I have included the relevant code, a brief explanation of each solution, and the dataset I used (`portugal.xlsx`).

---

## Q1: Derive the Following

**Q1** involves deriving the posterior distributions for linear regression parameters and the error variance when given a Gaussian likelihood. I show the derivation step by step, highlight how the likelihood and prior combine, and arrive at the conjugate inverse-gamma form.

---


## Q2: Perform Bayesian Linear Regression

**Q2** focuses on constructing a Bayesian linear regression model without using an inverse-gamma prior. I use normal priors for the regression coefficients (`pm.Normal`) and a half‐normal prior, then present MCMC results, posterior diagnostics, and posterior predictive checks.

---


## Q3: Perform Robust Bayesian Linear Regression

**Q3** covers fitting a Student‐\(t\) or scale‐mixture–based Bayesian regression model to handle outliers. I also manipulate the dataset to create artificial outliers, demonstrate how the robust regression model downweights them, and compute hat‐matrix diagonals to identify influential points.

---

## Dataset

The file **`portugal.xlsx`** (included in this repository) is the dataset I used for the examples in Q2 and Q3. It contains numeric and categorical variables; some columns are used as predictors, and one numeric column serves as the target.

---

**End of README**
