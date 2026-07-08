# Counterfactual Explanation using Trees (CET) for Loan Approval Systems

## Overview
Developed an Explainable AI framework using **Counterfactual Explanation Trees (CET)** to generate actionable recommendations for improving loan approval outcomes.

The system explains loan rejection decisions by suggesting optimal feature modifications required for approval, making credit decision models more transparent and interpretable.

## Key Features
- Generated actionable counterfactual explanations for rejected loan applications
- Automated counterfactual generation using **Random Forest, LightGBM, and TabNet** classifiers
- Designed a **stochastic local search algorithm** to identify cost-optimal feature modifications
- Improved interpretability of black-box machine learning models used in lending decisions

## Methodology
- Performed data preprocessing, missing value treatment, and class balancing using **SMOTE**
- Trained and evaluated multiple tree-based machine learning models
- Implemented group-wise Counterfactual Explanation framework
- Optimized recommendation cost using **MPS** and **TLPS** techniques

## Tech Stack
Python | Machine Learning | Random Forest | LightGBM | TabNet | SMOTE | Optimization

## Outcome
Built an interpretable machine learning framework that transforms loan rejection predictions into actionable recommendations, improving transparency in credit decision systems.
