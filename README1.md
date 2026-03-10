# 📊 Telecom Customer Churn Analysis — EDA

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)
![Type](https://img.shields.io/badge/Type-EDA-purple?style=flat)

> Exploratory Data Analysis on Telecom Customer Churn — uncovering key drivers like contract type, payment method, and tenure to support data-driven retention strategies.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset Description](#-dataset-description)
- [Tools & Technologies](#️-tools--technologies)
- [Project Structure](#-project-structure)
- [Key Analysis Performed](#-key-analysis-performed)
- [Key Insights](#-key-insights)
- [Visualizations](#-visualizations)
- [Conclusions](#-conclusions)
- [Future Work](#-future-work)
- [Author](#-author)

---

## 🔍 Project Overview

Customer churn is one of the most critical challenges faced by telecom service providers due to intense market competition and low switching costs. This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a Telecom Customer Churn dataset to:

- Understand customer behavior across demographics, services, and billing
- Identify key factors that influence a customer's decision to churn
- Extract actionable business insights to support retention strategies
- Lay a foundation for future predictive churn modeling

Even a modest reduction in churn rate can result in substantial revenue preservation, making this a high-impact analytical task.

---

## 📁 Dataset Description

The dataset contains **customer-level observations** with the following feature groups:

| Category | Features |
|---|---|
| **Demographics** | Gender, Senior Citizen, Partner, Dependents |
| **Services** | Phone, Internet, Online Security, Tech Support, Streaming TV/Movies |
| **Contract & Billing** | Contract Type, Payment Method, Paperless Billing |
| **Financials** | Monthly Charges, Total Charges |
| **Target** | **Churn** (Yes / No) |

---

## 🛠️ Tools & Technologies

- **Language:** Python 3.8+
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 📂 Project Structure

```
telecom-churn-eda/
│
├── Telecom_churn.ipynb          # Main EDA notebook
├── README.md                    # Project documentation
└── data/
    └── telecom_churn.csv        # Dataset (add your dataset here)
```

---

## 📈 Key Analysis Performed

- **Data Cleaning & Preprocessing** — Handling missing values, type corrections, and feature formatting
- **Univariate Analysis** — Distribution of individual features including churn rate
- **Bivariate Analysis** — Relationship between each feature and the churn target
- **Demographic Analysis** — Impact of gender, age, partner, and dependents on churn
- **Service Analysis** — Effect of internet type, security, and support subscriptions
- **Contract & Payment Analysis** — Churn rates across contract types and payment methods
- **Tenure & Financial Analysis** — How customer lifetime and charges relate to churn

---

## 🔑 Key Insights

1. 📋 **Contract Type** — Customers on **month-to-month contracts** have the highest churn rate. Long-term contracts (1 or 2 years) significantly reduce churn.

2. 💳 **Payment Method** — **Electronic check** users churn the most. Customers on automatic payment methods (credit card, bank transfer) show stronger retention.

3. 🔒 **Service Bundling** — Customers **without online security or tech support** are far more likely to churn. Bundled services act as retention mechanisms.

4. 📅 **Tenure** — New customers are most vulnerable to churning in the **early months**. Churn risk drops significantly as tenure grows.

5. 💰 **Monthly Charges** — Higher monthly charges correlate with increased churn, especially among short-tenure customers.

6. 👨‍👩‍👧 **Demographics** — Gender has minimal impact on churn. **Senior citizens** and customers **without partners or dependents** show slightly higher churn tendencies.

7. 🌐 **Internet Service** — **Fiber optic** users churn more than DSL users, potentially due to higher pricing and elevated service expectations.

---

## 📊 Visualizations

The notebook includes the following visualizations:
- Churn distribution (pie chart & count plot)
- Churn by contract type, payment method, and internet service
- Tenure distribution for churned vs. retained customers
- Monthly and total charges vs. churn
- Heatmap of feature correlations

---

## ✅ Conclusions

This analysis demonstrates that customer churn is primarily driven by:
- **Contractual flexibility** (month-to-month plans)
- **Pricing sensitivity** (high monthly charges, short tenure)
- **Service quality & support availability**
- **Payment convenience**

Demographic factors play a comparatively minor role. Effective churn reduction strategies should prioritize converting short-term customers to long-term contracts, promoting auto-payment enrollment, bundling essential services, and strengthening early onboarding experience.

---

## 🚀 Future Work

- [ ] Feature engineering for predictive modeling
- [ ] Build classification models (Logistic Regression, Random Forest, XGBoost)
- [ ] Hyperparameter tuning and model evaluation
- [ ] Deploy a churn prediction API or dashboard

---

## 👤 Author

**Mayank Yadav**  
📧 Feel free to connect on [LinkedIn](#) | [GitHub](#)

---

> ⭐ If you found this project helpful, consider giving it a star!
