[README_project19.md](https://github.com/user-attachments/files/25822016/README_project19.md)# ANOMALY-DETECTION-CREDIT-CARD-FRAUD
Detect fraudulent credit card transactions using 3 methods: Z-Score, IQR, and Isolation Forest on REAL data.

[Uploading README_project1# Anomaly Detection — Credit Card Fraud (284K Transactions)

## Overview
Anomaly detection on the **real Kaggle Credit Card Fraud dataset** — 284,807 transactions with only 492 frauds (0.17%). Compares three detection methods: Z-Score (statistical), IQR (robust statistical), and Isolation Forest (ML-based) on this extremely imbalanced real-world data.

**Built by:** Nithin Kumar Kokkisa — Senior Demand Planner with 12+ years at HPCL managing 180,000 MTPA facility, including process safety management.

---

## Dataset
- **Source**: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size**: 284,807 transactions (2 days of European cardholder activity)
- **Fraud**: 492 cases (0.17%) — extremely imbalanced
- **Features**: V1-V28 (PCA-transformed for privacy), Time, Amount

## Three Detection Methods

| Method | Type | Strength | Weakness |
|--------|------|----------|----------|
| **Z-Score** | Statistical | Simple, fast, interpretable | Univariate only |
| **IQR** | Statistical | No normality assumption | Univariate only |
| **Isolation Forest** | ML-based | Multivariate, no assumptions | Less interpretable |

## Key Insight
Isolation Forest outperforms statistical methods because fraud involves unusual **combinations** of features across 29 dimensions that single-variable methods miss. In fraud detection, **recall > precision** because missing a $10K fraud costs more than investigating a false alarm.

## Visualizations
- Amount/Time distributions, PCA feature analysis
- Anomaly score distributions, scatter plots
- Precision-Recall curve, confusion matrices
- Fraud pattern analysis (detected vs missed)

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **scikit-learn** (IsolationForest, StandardScaler)

---

## About
Part of a **30-project data analytics portfolio**. See [GitHub profile](https://github.com/Kokkisa) for the full portfolio.
9.md…]()

