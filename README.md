# 📉 Telecom Customer Churn — Exploratory Data Analysis

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-EDA-purple?style=for-the-badge)

**Uncovering why telecom customers leave — a deep-dive EDA into churn behaviour across contracts, payments, services, and demographics to support data-driven retention strategies.**

[📓 View Notebook](./Telecom_churn.ipynb) · [📄 Full Report](./Telecom_Churn_Continuous_Detailed_Report.pdf) · [🔗 LinkedIn](https://www.linkedin.com/in/mayank-yadav-82a6a6211)

</div>

---

## 📌 Project Overview

Customer churn is one of the most costly problems in the telecom industry. Acquiring a new customer costs **5× more** than retaining an existing one — making churn prediction and prevention a top business priority.

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on a Telecom Customer Churn dataset (7,000+ records) to:

- Identify the strongest drivers of customer churn
- Understand how contract type, billing, and services affect retention
- Uncover demographic patterns linked to churn behaviour
- Generate actionable business recommendations to reduce churn

---

## 🎯 Objectives

- Analyze churn patterns across demographics, services, and billing features
- Identify which customer segments are most at risk of churning
- Visualize key relationships between features and churn outcome
- Provide data-backed recommendations for retention strategy

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.8+** | Core programming language |
| **Pandas** | Data loading, cleaning & manipulation |
| **NumPy** | Numerical operations |
| **Matplotlib** | Base visualizations & charts |
| **Seaborn** | Statistical plots & heatmaps |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📂 Project Structure

```
Telecom_Churn/
│
├── Telecom_churn.ipynb                          # 📓 Main EDA Notebook
├── Telecom_Churn_Continuous_Detailed_Report.pdf # 📄 Full Analysis Report
└── README.md                                    # 📘 Project Documentation
```

---

## 📁 Dataset Description

The dataset contains **7,000+ customer-level records** with the following feature groups:

| Category | Features |
|----------|----------|
| **Demographics** | Gender, Senior Citizen, Partner, Dependents |
| **Services** | Phone, Internet, Online Security, Tech Support, Streaming TV/Movies |
| **Contract & Billing** | Contract Type, Payment Method, Paperless Billing |
| **Financials** | Monthly Charges, Total Charges |
| **Target Variable** | **Churn** (Yes / No) |

---

## 📊 Analysis Breakdown

### 1️⃣ Data Cleaning & Preprocessing
- Handled missing values and fixed data type inconsistencies
- Converted `TotalCharges` from object to numeric
- Encoded categorical features for analysis

### 2️⃣ Univariate Analysis
- Distribution of all individual features
- Overall churn rate in the dataset
- Feature-wise value counts and proportions

### 3️⃣ Bivariate Analysis
- Relationship between each feature and the churn target
- Churn rate comparison across all categorical groups
- Correlation between numerical features and churn

### 4️⃣ Demographic Analysis
- Impact of gender, age group, partner, and dependents on churn
- Senior citizen churn behaviour

### 5️⃣ Service & Contract Analysis
- Effect of internet type, security, and support services on churn
- Churn rates across contract types (monthly, 1-year, 2-year)
- Payment method vs churn correlation

### 6️⃣ Financial Analysis
- Monthly charges distribution for churned vs retained customers
- Total charges vs tenure relationship
- High-value customer churn risk

---

## 🔑 Key Insights

> 📋 **Contract Type is the #1 Churn Driver** — Month-to-month customers churn at nearly **3× the rate** of annual contract customers. Long-term contracts are the strongest retention tool.

> 💳 **Payment Method Matters** — Electronic check users show the highest churn. Customers on automatic payments (credit card, bank transfer) are significantly more loyal.

> 🔒 **Service Bundling Reduces Churn** — Customers without online security or tech support are far more likely to leave. Bundled services act as powerful retention anchors.

> 📅 **Early Tenure = High Risk** — New customers are most vulnerable in the **first 3 months**. Churn risk drops sharply as tenure increases beyond 12 months.

> 💰 **High Charges + Short Tenure = Danger Zone** — Customers paying high monthly fees without the loyalty of long tenure show the highest churn probability.

> 🌐 **Fiber Optic Users Churn More** — Despite being a premium service, fiber optic users churn more than DSL users — likely due to unmet expectations vs pricing.

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/Mayank-589/Telecom_Churn.git

# 2. Navigate into the project folder
cd Telecom_Churn

# 3. Install required libraries
pip install pandas numpy matplotlib seaborn jupyter

# 4. Launch Jupyter Notebook
jupyter notebook Telecom_churn.ipynb
```

---

## 📈 Visualizations Included

- ✅ Churn distribution pie chart & count plot
- ✅ Churn rate by contract type bar chart
- ✅ Payment method vs churn comparison
- ✅ Tenure distribution for churned vs retained customers
- ✅ Monthly charges vs churn box plots
- ✅ Internet service type vs churn
- ✅ Feature correlation heatmap
- ✅ Senior citizen and demographic churn analysis

---

## 💡 Business Recommendations

Based on the analysis, the following retention strategies are recommended:

| Strategy | Target Segment | Expected Impact |
|----------|---------------|-----------------|
| Offer discounts for annual contracts | Month-to-month customers | High |
| Promote auto-payment enrollment | Electronic check users | Medium-High |
| Bundle security & support services | Customers without add-ons | Medium |
| Strengthen early onboarding (0–3 months) | New customers | High |
| Review fiber optic pricing & service quality | Fiber optic users | Medium |

---

## 🔮 Future Scope

- [ ] Build a churn prediction model (Logistic Regression, Random Forest, XGBoost)
- [ ] Perform feature engineering for improved model accuracy
- [ ] Deploy a churn prediction API using Flask or FastAPI
- [ ] Create an interactive Streamlit dashboard for business users
- [ ] Conduct customer segmentation using clustering techniques

---

## 👤 Author

**Mayank Yadav**
2nd Year Data Science Student

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/mayank-yadav-82a6a6211)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/Mayank-589)

---

## ⭐ Support

If you found this project insightful, please consider giving it a **star** ⭐ — it helps others discover the work and encourages continued development!

---

<div align="center">
<i>Made with 📊 and 🐍 by Mayank Yadav</i>
</div>
