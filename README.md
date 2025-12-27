# Credit Risk Modeling and Profit-Optimized Underwriting

This project demonstrates how an interpretable credit risk model can be used to support real-world underwriting decisions in a banking context.

## Overview
- Logistic regression probability-of-default (PD) model
- Bank-style data preparation and missing-value treatment
- Risk decile segmentation for underwriting
- Expected loss framework (PD × LGD × EAD)
- Profit-maximizing approval cutoff analysis
- Sensitivity analysis under different revenue assumptions

## Model Performance
- AUC ≈ 0.86
- KS ≈ 0.55

## Key Result
Rejecting the top 10% riskiest applicants maximized profit per applicant while maintaining a 90% approval rate, illustrating how optimal credit policy depends on both risk ranking and business economics.

## Notes
The dataset used in this project is publicly available (Give Me Some Credit, Kaggle) and is not included in this repository.
