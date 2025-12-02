# AI Decision Tree Project

Professional implementation of Decision Trees and Random Forests with comprehensive academic report.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-v1.3+-orange)](https://scikit-learn.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Key Results

| Dataset | Model            | Accuracy |
|---------|------------------|----------|
| Iris    | Decision Tree    | **95.3%** |
| Iris    | Random Forest    | **97.8%** |
| Wine    | Decision Tree    | **92.1%** |
| Wine    | Random Forest    | **96.6%** |

## Project Report
[Download Full PDF Report](AI%20Decision%20Tree%20Project%20Report.pdf) (English + Persian – 20 pages)

**Executive Summary (from Report):**  
This project explores Decision Tree classifiers using CART algorithm on UCI datasets (Iris, Wine). Key experiments include hyperparameter tuning (max_depth: 3-10, min_samples_split: 2-5), cross-validation (5-fold), and ensemble methods like Random Forest (n_estimators: 100-200). Results show Random Forest outperforming single trees by 3-5% in accuracy, precision, recall, and F1-score. Visualizations cover tree structures, confusion matrices, and ROC curves. Conclusions highlight interpretability vs. overfitting trade-offs, with code optimized for reproducibility.

## Quick Install & Run (30 seconds)

```bash
git clone https://github.com/aibgr/Tree-Project.git
cd Tree-Project
pip install -r requirements.txt
