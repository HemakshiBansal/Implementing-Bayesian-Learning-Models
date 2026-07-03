# Implementing-Bayesian-Learning-Models

This repository contains coursework for **CGS698C: Bayesian Models & Data Analysis**, taught by Prof. Himanshu Yadav. It includes the assignment questionnaires and their corresponding solutions (R/Python code and analysis notebooks).

## Repository Structure

| File | Description |
|------|-------------|
| `Assignment-01-Questions.pdf` | Foundational probability theory — set operations, discrete random variables, binomial and Poisson distributions |
| `Assignment-02-Questions.pdf` | Continuous random variables, normal and Beta distributions, likelihood functions |
| `Assignment-03-Questions.pdf` | Bayes' theorem for statistical inference, posterior derivation, and Bayesian model building |
| `Assignment-04-Questions.pdf` | Computational posterior estimation — Importance Sampling, MCMC, and Hamiltonian Monte Carlo |
| `Assignment-05-Questions.pdf` | Bayesian regression models — linear regression and Poisson regression using `brms` |
| `Assignment-06-Questions.pdf` | Model comparison — log pointwise predictive density, in/out-of-sample deviance, LOO-CV, and marginal likelihood |

## Assignment Summaries

**Assignment 1:** Theoretical, non-coding assignment covering set theory, sample spaces, and probability mass functions (binomial, Poisson) applied to a word-recognition and COVID infection-rate scenario.

**Assignment 2:** Explores continuous random variables and probability density functions (Normal, Beta), the concept of the likelihood function, and practical use of R's `dnorm`, `pnorm`, and `rnorm`.

**Assignment 3:** Introduces Bayes' rule for parameter estimation. Includes deriving a posterior distribution analytically for a Binomial-Beta setup, and building two competing cognitive models (Null vs. Lexical-Access) to test whether non-words take longer to recognize than words, using prior predictive checks.

**Assignment 4:** Estimates posterior distributions using non-analytical methods — Importance Sampling, Markov Chain Monte Carlo (MCMC), and a custom-built Hamiltonian Monte Carlo (HMC) sampler — applied to a lexical-access mixture model and a Normal-Normal model.

**Assignment 5:** Fits Bayesian linear and Poisson regression models using `brms`. Covers a power-posing/testosterone dataset (linear regression with weakly informative priors) and a syntactic crossing-dependencies dataset (Poisson regression, model comparison via k-fold cross-validation).

**Assignment 6:** Covers information-theoretic model comparison — computing lppd, in-sample and out-of-sample deviance, leave-one-out cross-validation (LOO-CV), and marginal likelihood with prior sensitivity analysis using Monte Carlo integration.

## Tools Used
- R (`brms`, `truncnorm`, `ggplot2`)
- Bayesian inference methods: Grid Approximation, Importance Sampling, MCMC, Hamiltonian Monte Carlo
- Model comparison: LOO-CV, marginal likelihood, deviance

## Course Info
**Course:** CGS698C — Bayesian Models & Data Analysis
**Instructor:** Prof. Himanshu Yadav
