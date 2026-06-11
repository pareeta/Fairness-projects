# Fair Stroke Risk Prediction with LightGBM (Educational Demo)

## Overview

This repository contains a simplified educational implementation of a fairness-aware stroke risk prediction workflow using LightGBM.

The notebook was created to understand the concepts presented in research on fairness-aware machine learning for healthcare, particularly stroke risk prediction in patients with Atrial Fibrillation (AFib).

> **Note:** This is **not** the official implementation of the research paper and does **not** reproduce its published results. It is intended solely for learning and experimentation.

---

## Objectives

- Understand how LightGBM can be used for stroke risk prediction.
- Learn the concept of subgroup fairness in machine learning.
- Calculate overall AUROC and subgroup-specific AUROC.
- Measure performance disparity between racial groups.
- Demonstrate a simple fairness-aware scoring approach.
- Apply race-specific decision thresholds using Youden's J statistic.

---

## Workflow

1. Create a toy EHR-like dataset.
2. Preprocess the data.
3. Train a LightGBM classifier.
4. Compute overall AUROC.
5. Compute race-wise AUROC.
6. Measure subgroup disparity.
7. Calculate a fairness-aware tuning score.
8. Determine race-specific thresholds using Youden's J statistic.
9. Generate final predictions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM

---

## Important Disclaimer

This project uses a small synthetic dataset for demonstration purposes.

It does **not**:
- use the All of Us Research Program dataset,
- reproduce the complete methodology of the original paper,
- implement the complete fairness optimization framework,
- claim any clinical validity.

The implementation is only meant to help understand the underlying concepts.

---

## Educational Purpose

This notebook was created as a personal learning exercise to better understand:
- Fairness-aware machine learning
- Healthcare AI
- LightGBM-based prediction models
- AUROC-based evaluation
- Subgroup fairness analysis
- Race-specific thresholding

---

## Future Improvements

- Hyperparameter tuning
- 5-fold cross-validation
- Fairness-aware model selection
- Fairlearn integration
- Additional fairness metrics
- SHAP explainability
- More realistic EHR feature engineering

---

## License

This repository is shared for educational and research learning purposes.
