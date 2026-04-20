
# K-Nearest Neighbors (KNN) Classification Project

---

## Overview

This project applies the **K-Nearest Neighbors (KNN)** algorithm to classify data points from a dataset (`KNN_Project_Data`). The goal is to build, evaluate, and tune a KNN classifier by following the full machine learning pipeline — from data loading and preprocessing through model training, evaluation, and hyperparameter selection using the **elbow method**.

---

## Results Summary

| Model | Accuracy | Precision (0) | Recall (0) | Precision (1) | Recall (1) |
|---|---|---|---|---|---|
| KNN (K = 1) | 89.67% | 0.85 | 0.93 | 0.94 | 0.87 |
| KNN (K = 3) | **92.00%** | **0.88** | **0.96** | **0.96** | **0.89** |

Tuning from K = 1 to K = 3 improved overall accuracy by **+2.33 percentage points** and reduced false positives/negatives across both classes.
