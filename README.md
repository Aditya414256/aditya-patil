# 🛒 Smart E-Commerce Intelligence System

> **SPYTHON: Rise of the Machine Learning – Phase 2**
> Submitted as part of the 3-Day Machine Learning Workshop by the **@fetch.ai.rcpit** Developer Club.

---

## 📌 Project Overview

This project builds a complete end-to-end supervised Machine Learning pipeline on a real-world inspired e-commerce customer dataset. It covers two core ML tasks:

| Task | Target Variable | Problem Type |
|------|----------------|--------------|
| Predict Annual Spending | `Annual_Spending` | **Regression** |
| Predict Customer Churn | `Churn` (0 / 1) | **Classification** |

---

## 📂 Repository Structure

```
├── SMART E-COMMERCE INTELLIGENCE SYSTEM - (ML Project).ipynb  ← Main notebook
├── Project-Dataset/
│   ├── ecommerce_customers_200_clean.csv                       ← 200-customer dataset
│   └── ecommerce_data_dictionary.csv                          ← Feature descriptions
└── README.md
```

---

## 📊 Dataset

- **Source:** Synthetic e-commerce dataset (educational use)
- **Rows:** 200 customers
- **Columns:** 18 features
- **Key features:** Age, Income, Membership_Type, Visits_Per_Month, Cart_Abandonment_Rate, Days_Since_Last_Purchase, Annual_Spending, Churn

---

## 🤖 Models Used

### Part A — Regression (Predicting Annual Spending)
| Model | MAE | RMSE | R² |
|-------|-----|------|-----|
| Linear Regression | — | — | — |
| Decision Tree Regressor | — | — | — |
| Random Forest Regressor ⭐ | — | — | — |

### Part B — Classification (Predicting Customer Churn)
| Model | Accuracy | F1-Score | ROC-AUC |
|-------|----------|----------|---------|
| Logistic Regression | 0.725 | 0.353 | 0.702 |
| Decision Tree Classifier | — | — | — |
| Random Forest Classifier ⭐ | — | — | — |

---

## 🧪 ML Pipeline

```
Business Question
      ↓
Dataset (200 Customers, 18 Columns)
      ↓
Feature Selection & Target Identification
      ↓
Preprocessing (StandardScaler + OneHotEncoder via ColumnTransformer)
      ↓
Train / Test Split (80% / 20%)
      ↓
Model Training (Linear Reg / Decision Tree / Random Forest)
      ↓
Evaluation (MAE, RMSE, R², Accuracy, Precision, Recall, F1, ROC-AUC)
      ↓
Feature Importance & Interpretation
      ↓
Interactive Student Prediction Experiment
```

---

## 💡 Key Concepts Covered

- **Supervised Learning:** Regression vs Classification
- **Preprocessing:** `StandardScaler`, `OneHotEncoder`, `ColumnTransformer`
- **Model Families:** Linear Regression, Logistic Regression, Decision Trees, Random Forests
- **Evaluation Metrics:** MAE, RMSE, R², Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix
- **Feature Importance:** Random Forest feature contribution analysis
- **Mini-Challenges:** Sensitivity analysis on model predictions

---

## 🚀 How to Run

### Option A — Google Colab (Recommended)
1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload `ecommerce_customers_200_clean.csv` when prompted
3. Run all cells: `Runtime → Run all`

### Option B — Local Environment
```bash
pip install scikit-learn pandas numpy matplotlib seaborn
jupyter notebook "SMART E-COMMERCE INTELLIGENCE SYSTEM - (ML Project).ipynb"
```

---

## 📝 Student Mini-Challenges

The notebook includes four mini-challenges at the end:

1. **Regression Sensitivity** — Test how changing `Visits_Per_Month`, `Avg_Order_Value`, `Products_Bought` affects predicted spending
2. **Churn Sensitivity** — Test how increasing `Days_Since_Last_Purchase`, `Cart_Abandonment_Rate`, `Support_Tickets` changes churn probability
3. **Model Comparison** — Explain why Linear Regression, Decision Trees, and Random Forests behave differently
4. **Business Interpretation** — Identify customer patterns associated with higher spending or higher churn risk

---

## 🎓 Workshop Details

- **Event:** SPYTHON: Rise of the Machine Learning – Phase 2
- **Organiser:** Fetch.ai Developer Club — **@fetch.ai.rcpit**
- **Duration:** 3-Day Machine Learning Workshop
- **Submission:** GitHub repository upload with `@fetch.ai.rcpit` mentioned

---

## 👤 Author

| Detail | Info |
|--------|------|
| **Name** | Aditya4142 |
| **GitHub** | [@Aditya4142](https://github.com/Aditya4142) |
| **Workshop** | @fetch.ai.rcpit SPYTHON ML Workshop |

---

*Keep Learning. Keep Coding. Keep Building!* 🚀💙

*– Team Fetch.ai Club*
