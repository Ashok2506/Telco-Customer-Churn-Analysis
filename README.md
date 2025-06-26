# 📉 Telco Customer Churn Analysis
A detailed data analysis project on customer churn at a telecom company.  
The goal is to identify factors influencing churn and uncover business insights to reduce customer loss.

---

## 📌 Project Objectives

- Understand churn rate and customer behavior
- Explore key features that drive churn (contract type, payment method, etc.)
- Visualize patterns and trends to support data-driven decision-making

---

## 📂 Dataset Info

- Dataset: [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Records: 7,043 rows
- Features: 21 columns (numerical + categorical)
- Target variable: `Churn`

---

## ⚙️ Tools & Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🔍 Key Steps

### 1. Data Cleaning
- Converted `TotalCharges` to numeric
- Removed rows with tenure = 0
- Checked nulls, dtypes, and duplicates

### 2. EDA (Exploratory Data Analysis)
- **Churn Rate**: 26.6%
- Contract Type: Month-to-month customers churn the most (~42%)
- Payment Method: Electronic check users have ~45% churn
- Numerical Features:
  - Churned users have lower `tenure` and `TotalCharges`
  - Higher `MonthlyCharges` → higher churn

### 3. Visualizations
- Bar plots, Box plots, Crosstabs

---

## 📊 Insights

- Customers on month-to-month plans with electronic check payments are most likely to churn.
- Loyal users (higher tenure) are associated with lower churn and higher total charges.

---

## 🚀 Next Steps

- Model building (Logistic Regression, Decision Trees)
- Dashboarding in Excel / Tableau
- Create a business action plan for retention

---

## ✅ How to Run

1. Clone this repository
2. ****
