---
layout: page
title: Early Sepsis Prediction
description: Machine learning pipeline for early sepsis detection from ICU time-series clinical data.
importance: 2
category: research
github: https://github.com/Advika1030/EarlySepsisPrediction
---

**Jun 2025 · Clinical ML · PhysioNet 2019 · Python**

Built a machine learning system to predict sepsis at early stages using ICU time-series data from the 2019 PhysioNet Challenge, with emphasis on reducing missed critical cases.

### Problem

ICU sepsis datasets contain irregular time series, heavy missingness, and severe class imbalance—making early detection difficult without careful preprocessing and evaluation design.

### Approach

- Imputed missing clinical values using linear interpolation and MICE
- Engineered time-series features from longitudinal ICU records
- Trained and compared logistic regression and XGBoost models
- Optimized primarily for **recall** to minimize false negatives in a high-risk clinical setting

### Results

- Achieved up to **80% recall**, prioritizing early detection over raw accuracy
- Built a reproducible training and evaluation pipeline for sepsis risk scoring

### Tech stack

Python, scikit-learn, XGBoost, pandas, time-series imputation, class-imbalance handling

**Repository:** [Advika1030/EarlySepsisPrediction](https://github.com/Advika1030/EarlySepsisPrediction)
