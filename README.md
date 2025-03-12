# HW7
# Homework 7 Solutions

This repository contains my solutions for Homework 7 from [Course Name/Class Info Here]. I have included the relevant code, a brief explanation of each solution, and the dataset I used (`portugal.xlsx`).

---

## Q1: Derive the Following

**Q1** involves deriving the posterior distributions for linear regression parameters and the error variance when given a Gaussian likelihood. I show the derivation step by step, highlight how the likelihood and prior combine, and arrive at the conjugate inverse-gamma form for \(\sigma^2\).

---

## [Optional] Q1 Extra

In this section, I demonstrate how setting certain priors for \(\beta\) (e.g., normal or Laplace) corresponds to ridge or lasso‐style regularization in a Bayesian framework. The derivation shows that Bayesian methods naturally incorporate penalty terms through the prior.

---

## Q2: Perform Bayesian Linear Regression

**Q2** focuses on constructing a Bayesian linear regression model without using an inverse-gamma prior for \(\sigma\). I use normal priors for the regression coefficients (`pm.Normal`) and a half‐normal prior for \(\sigma\), then present MCMC results, posterior diagnostics, and posterior predictive checks.

---

## [Optional] Q2 Extra: Perform Generalized Bayesian Linear Regression

Here, I replace the usual normal residual distribution with an alternative (e.g., Poisson or logistic) and use an appropriate link function for a generalized linear model. The code demonstrates how to adapt the basic PyMC model to other likelihoods and link functions.

---

## Q3: Perform Robust Bayesian Linear Regression

**Q3** covers fitting a Student‐\(t\) or scale‐mixture–based Bayesian regression model to handle outliers. I also manipulate the dataset to create artificial outliers, demonstrate how the robust regression model downweights them, and compute hat‐matrix diagonals to identify influential points.

---

## Dataset

The file **`portugal.xlsx`** (included in this repository) is the dataset I used for the examples in Q2 and Q3. It contains numeric and categorical variables; some columns are used as predictors, and one numeric column serves as the target.

---

**End of README**
