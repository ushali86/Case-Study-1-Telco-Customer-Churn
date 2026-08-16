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

---

# Case Study 2: ChurnGuard

## 🎯 Business Framing

ChurnGuard is a telecom customer retention system designed to identify customers who are likely to leave the company.

The goal is to identify high-risk customers early and take preventive retention actions.

## 🤖 Machine Learning Problem

- **Problem Type:** Binary Classification
- **Target Variable:** `Churn`
- **Churn = Yes:** Customer leaves
- **Churn = No:** Customer stays

## 💰 False Positive vs False Negative

### False Positive

The model predicts that a customer will churn, but the customer actually stays.

**Business impact:** The company may unnecessarily spend money on discounts, offers, and retention campaigns.

### False Negative

The model predicts that a customer will stay, but the customer actually churns.

**Business impact:** The company loses the customer and future recurring revenue.

### Cost Comparison

| Error | Business Impact |
|---|---|
| False Positive | Unnecessary retention cost |
| False Negative | Lost customer and future revenue |

For ChurnGuard, **False Negative is generally more costly**.

## 📏 Success Metrics

### Primary Metric: Recall

Recall for the `Churn = Yes` class is the primary metric because the company wants to identify as many actual churners as possible.

### Secondary Metric: Precision

Precision helps control unnecessary retention offers.

### Supporting Metric: F1-Score

F1-Score provides a balance between Precision and Recall.

## 🚦 Business Decision Strategy

| Churn Risk | Recommended Action |
|---|---|
| High | Contact customer and provide retention offer |
| Medium | Personalized engagement/offer |
| Low | Normal customer communication |

## 🏁 Business Goal

The ultimate goal of ChurnGuard is to:

- Reduce customer churn
- Reduce unnecessary retention spending
- Protect recurring revenue
- Improve customer retention
- Preserve customer lifetime value

## 📁 ChurnGuard Notebook

Detailed business framing is available in:

`ChurnGuard_Business_Framing.ipynb`
