#  ML-Based Survival Modeling in Metastatic Melanoma
Machine learning–based survival prediction in metastatic melanoma using TCGA RNA-seq and clinical data.

## Overview
This project builds an end-to-end machine learning pipeline for survival prediction
in metastatic melanoma, integrating high-dimensional RNA-sequencing data with
clinical and pathological features from TCGA.

The goal is to compare multiple survival modeling approaches under the same
data and evaluation framework, with an emphasis on predictive performance,
robustness, and feature interpretability.

## Methods
The analysis pipeline includes:
- Data preprocessing and feature standardization for high-dimensional genomics data
- Univariate Cox proportional hazards (Cox-PH) screening
- Regularized and ensemble survival models:
  - LASSO-penalized Cox regression
  - CoxBoost
  - Random Survival Forest (RSF)
- Model evaluation using concordance-based metrics (e.g., C-index)
- Permutation-based feature importance and stability analysis across multiple splits
- Post hoc correlation analysis among top-ranked features

  
