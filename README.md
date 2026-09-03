# End-to-End E-Commerce Data Science & Predictive Analytics Suite

An end-to-end data analytics and machine learning suite built on transactional e-commerce data. This project covers customer lifetime segmentation, churn prediction, cross-selling analysis, time-series revenue forecasting, retention cohort modeling, and financial payment friction analysis.

---

## 📌 Project Overview

This repository is structured into 5 modular, standalone analysis notebooks:

| # | Notebook | Core Domain / Methods | Key Results |
|---|---|---|---|
| **01** | `01_rfm_customer_segmentation_and_churn.ipynb` | RFM Analysis, K-Means Clustering, Random Forest, SMOTE | Improved Churn Recall from 24% to 73% using SMOTE |
| **02** | `02_market_basket_analysis.ipynb` | Association Rule Mining, Apriori Algorithm | Evaluated cross-purchasing affinity across order baskets |
| **03** | `03_revenue_time_series_forecasting.ipynb` | Time-Series Decomposition, Holt-Winters Exponential Smoothing | Out-of-sample 30-day sales forecast (MAE: 9.72, RMSE: 11.59) |
| **04** | `04_cohort_analysis_and_retention.ipynb` | Customer Retention Indexing, Cohort Heatmaps | Mapped monthly customer drop-off across cohort lifecycles |
| **05** | `05_payment_friction_and_financial_risk.ipynb` | Chi-Square Test of Independence, Inferential Statistics | Analyzed payment channel conversion efficiency vs. order status |

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.10+
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning & Modeling:** Scikit-Learn, Imbalanced-Learn (SMOTE)
* **Statistical Modeling:** Statsmodels, SciPy, MLxtend
* **Data Visualization:** Matplotlib, Seaborn
