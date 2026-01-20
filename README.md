This project was completed as part of the [Insert Course Name/Number Here] course and focuses on applying classification techniques to solve a critical e-commerce business problem.

## 🎯 Goal & Problem Definition

The core objective is to build a predictive model that can identify **High-Value Customers** (top 20% spenders) from an online retail dataset. This is a **Binary Classification** problem designed to enable strategic marketing resource allocation.

### Business Problem:
Marketing resources are finite. By accurately predicting which customers are most likely to be high-value, a business can **prioritize** its most expensive campaigns, maximizing **Return on Investment (ROI)** and customer lifetime value.

## 🛠️ Technical Overview

| Component | Details |
| :--- | :--- |
| **Dataset** | Online Retail Transactional Data (Sampled) |
| **Problem Type** | Binary Classification |
| **Model** | **Logistic Regression** |
| **Key Techniques** | Data Cleaning, Feature Engineering (RFM-derived features), Standard Scaling |

## 📈 Key Results & Business Impact

The model was specifically tuned to achieve high **Precision**, as the cost of a **False Positive** (wasting money on a low-value customer) is higher than the cost of a **False Negative** (missing a high-value customer).

| Metric | Value | Interpretation |
| :--- | :---: | :--- |
| **Precision (High-Value)** | **90%** | When the model predicts a customer is high-value, it is correct 9 out of 10 times. This provides **high confidence** for marketing decisions. |
| **Recall (High-Value)** | 65% | The model captures 65% of all truly high-value customers. |
| **Overall Accuracy** | 91% | The overall rate of correct predictions. |

### Model Interpretability (Logistic Regression Coefficients)
The use of Logistic Regression allowed for clear interpretation of the features driving the prediction. The analysis showed that **purchase volume** (Total Items and Total Invoices) was the strongest positive predictor of high customer value.


**Contact:** [Insert LinkedIn or Email Here]
