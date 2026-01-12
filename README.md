# Secure Care Analytics

**Privacy-Aware Predictive Modeling for Health Tech (Simulated Case Study)**

## Overview

This repository contains a simulated, end-to-end data science case study inspired by the operational challenges faced by modern mental health platforms.

The project demonstrates how **predictive modeling, bias-aware feature engineering, and privacy-preserving techniques** can be combined to support:

* Equitable care navigation
* Revenue cycle and resource planning
* HIPAA-aligned data practices

All data used is anonymized and intended solely for methodological demonstration.


## Business Problems Addressed

1. **Care Navigation & Patient Stratification**
   Identifying patients with similar profiles to enable more personalized and equitable care pathways.

2. **Revenue Cycle & Utilization Forecasting**
   Predicting benefit utilization and claim approval likelihood to reduce operational friction and improve planning.

3. **Privacy & Trust by Design**
   Ensuring sensitive patient data can be analyzed securely without exposing personally identifiable information.


## Key Results

* **Bias-Aware Modeling:**
  Feature scaling was shown to be essential for preventing socioeconomic bias in patient similarity modeling.

* **Predictive Performance:**
  Machine learning models significantly outperformed baseline heuristics (F1 ≈ 0.93 vs ~0.20).

* **Privacy Without Tradeoffs:**
  A linear algebra–based data obfuscation technique preserved model accuracy exactly
  *(RMSE raw = RMSE obfuscated)*.
  

## Technical Approach (High Level)

* **Models:** kNN (cohorting), Logistic Classification, Linear Regression
* **Validation:** Baseline comparisons, appropriate metrics (F1, RMSE)
* **Privacy:** Invertible matrix-based feature obfuscation with analytical proof
* **Focus:** Interpretability, auditability, and operational relevance


## Repository Structure

* `notebook.ipynb` — Main analysis and modeling workflow
* `README.md` — Project overview and results


## Why This Project Matters

Healthcare analytics requires more than accuracy.
This project demonstrates how **responsible machine learning** can scale insight while preserving:

* Patient trust
* Regulatory alignment
* Operational clarity
  

## Author

**Sebastian Méndez Ramírez**
