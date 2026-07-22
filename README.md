# Financial Fraud Detection Analysis

## Project Overview
This project analyzes financial fraud detection 
patterns using a dataset of 5 million financial 
transaction records. The analysis was conducted 
using Python in Jupyter Notebook and an interactive 
dashboard was created using Microsoft Power BI.

## Dataset
- Source: Kaggle — Financial Fraud Detection Dataset
- Total Records: 5,000,000
- Total Columns: 18
- Fraud Cases: 179,553 (3.59%)
- Fraud Type: Card-Not-Present Fraud Only

## Tools and Technologies Used
- Python 3.13
- Jupyter Notebook
- pandas — Data cleaning and manipulation
- matplotlib — Data visualization
- seaborn — Statistical graphics
- scipy.stats — Hypothesis testing
- Microsoft Power BI — Interactive dashboard

## Project Structure
- Data cleaning and preparation
- Exploratory data analysis (10 charts)
- Hypothesis testing (3 t-tests)
- Interactive Power BI dashboard

## Key Findings
1. Only 3.59% of transactions are fraudulent
   — severe class imbalance
2. Fraud rate is equal (~3.59%) across ALL 
   transaction types, payment channels, devices,
   merchant categories, locations and hours
3. All 3 hypothesis tests failed to reject null 
   hypothesis:
   - Transaction Amount: p-value = 0.7092
   - Geo Anomaly Score: p-value = 0.4872
   - Velocity Score: p-value = 0.4079
4. Fraudulent transactions are statistically 
   indistinguishable from legitimate transactions
   — behavioral mimicry confirmed

## Main Conclusion
Fraudsters in this dataset deliberately copy normal 
customer behavior across all measurable dimensions 
making traditional rule-based detection ineffective.
This finding highlights the need for machine learning
based multi-variable fraud detection systems.

## Charts Created
- Figure 1: Fraud vs Non-Fraud Distribution
- Figure 2: Fraud Rate by Transaction Type
- Figure 3: Fraud Rate by Payment Channel
- Figure 4: Fraud Rate by Device Used
- Figure 5: Fraud Rate by Merchant Category
- Figure 6: Transaction Amount Distribution
- Figure 7: Average Geo Anomaly Score
- Figure 8: Average Velocity Score
- Figure 9: Fraud Rate by Hour of Day
- Figure 10: Fraud Rate by Location
- Figure 11: Power BI Interactive Dashboard

## Hypothesis Testing Results
| Hypothesis | Variable | P-Value | Result |
|---|---|---|---|
| H1 | Transaction Amount | 0.7092 | Not Significant |
| H2 | Geo Anomaly Score | 0.4872 | Not Significant |
| H3 | Velocity Score | 0.4079 | Not Significant |

## Recommendations
- Implement machine learning models (Random Forest,
  Gradient Boosting) for fraud detection
- Apply SMOTE to handle class imbalance
- Build individual customer behavioral profiles
- Implement real-time fraud detection systems
- Regularly retrain models to handle concept drift

## Academic Context
This project was completed as part of final year 
project work at Amity University Online.

Student: Ruchita Savant
Tool Used: Python, Power BI, Claude AI (learning assistant)