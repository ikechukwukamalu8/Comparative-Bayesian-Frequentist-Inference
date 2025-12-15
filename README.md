# Comparative Bayesian and Frequentist Inference for Overdispersed Count Data

## 🎯 Project Objective
This repository showcases a complete and rigorous statistical workflow for handling count data, focusing on the real-world problem of **overdispersion** (variance > mean). It provides a head-to-head comparison between **Maximum Likelihood Estimation (MLE)** and **Bayesian Markov Chain Monte Carlo (MCMC)** via JAGS.

## 🛠️ Key Technical Skills Demonstrated
* **Model Selection:** Justification of the Negative Binomial model over Poisson via **Overdispersion Testing (AER)**.
* **Comparative Inference:** Estimation of model parameters using both Frequentist (MLE/glm.nb) and Bayesian (JAGS) methods.
* **Statistical Rigor:** Implementation of modern validation techniques, including **Posterior Predictive Checks**.
* **Data Integrity:** Data cleaning, imputation, and aggregation of real-world COVID-19 vaccination data.

## 📄 Files
* `Negative_Binomial_Comparative_Analysis.R`: Complete script containing data processing, MLE fit, Overdispersion Test, Bayesian JAGS model, parameter comparison, and Posterior Predictive Check.
* `EU_COVID19_Vaccination_Counts.csv`: The required data file for full script reproducibility.
