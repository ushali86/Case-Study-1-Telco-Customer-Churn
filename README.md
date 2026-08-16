# Case Study 1: Telco Customer Churn

## 👤 Author
Ushali

## 📌 Business Problem

Telecom companies lose revenue when customers leave their services.
The objective of this case study is to predict whether a customer is likely to churn or stay.

## 📊 Dataset

**Dataset:** Telco Customer Churn

**Rows:** 7,043  
**Columns:** 21

The dataset contains customer demographic information, account information, services used, contract details, charges, and churn status.

## 🎯 Problem Type

### Binary Classification

The target variable is:

`Churn`

It has two possible outcomes:

- `Yes` → Customer will churn
- `No` → Customer will stay

Therefore, this is a **binary classification problem**.

## 📈 Churn Distribution

- Customers who stayed: **5,174 (73.46%)**
- Customers who churned: **1,869 (26.54%)**

## 🎯 Business Objective

The goal is to identify customers who are likely to leave the telecom company so that the business can take preventive actions such as:

- Customer retention offers
- Discounts
- Better customer support
- Personalized plans
- Service improvements

## 📏 Success Metric

### F1-Score

F1-Score is selected as the primary success metric because both **Precision and Recall** are important.

- **False Positive:** The company spends retention resources on a customer who would not have churned.
- **False Negative:** The company fails to identify a customer who actually churns.

F1-Score provides a balance between Precision and Recall.

## 📁 Project Files

| File | Description |
|---|---|
| `telco_customer_churn.ipynb` | Jupyter Notebook containing the analysis |
| `WA_Fn-UseC_-Telco-Customer-Churn.csv` | Telco customer churn dataset |

## 🛠️ Technologies Used

- Python
- Pandas
- Jupyter Notebook
- GitHub

## ✅ Conclusion

The Telco Customer Churn problem is a **binary classification problem** because the target variable `Churn` contains two classes: `Yes` and `No`.

The primary business success metric selected is **F1-Score**, which balances Precision and Recall and helps the company identify potential churners effectively.
