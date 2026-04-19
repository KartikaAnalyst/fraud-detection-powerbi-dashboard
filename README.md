# Fraud Detection Analysis Dashboard | Power BI Project

## Project Overview

This project is an interactive **Power BI dashboard** developed to analyze financial transaction data and identify potentially fraudulent activities using risk indicators, transaction behavior, and user patterns.

The dashboard provides meaningful insights into suspicious transactions based on payment methods, devices used, transaction locations, account history, and transaction frequency.

---

## Objective

To build a dynamic fraud detection dashboard that helps businesses monitor risky transactions, detect anomalies, and support faster decision-making.

---

## Tools & Technologies Used

- Power BI  
- Power Query  
- DAX (Data Analysis Expressions)  
- Excel / CSV Dataset  
- Data Cleaning & Transformation  

---

## Dataset Information

The dataset contains transaction-level data with the following fields:

- Transaction_ID  
- User_ID  
- Transaction_Amount  
- Transaction_Type  
- Time_of_Transaction  
- Is Risky?  
- Device_Used  
- Location  
- Previous_Fraudulent_Transactions  
- Account_Age  
- Number_of_Transactions_Last_24H  
- Payment_Method  
- Fraudulent  

---

## Dashboard Features

### KPI Cards

- **Total Transactions:** 382K  
- **Total Users:** 51K  
- **Total Risky Users:** 2,552  

### Visualizations Included

- Pie Chart: Risky vs Non-Risky Transactions  
- Bar Chart: Transactions by Payment Method  
- Map: Transactions by Location  
- Slicers:
  - Payment Method  
  - Device Used  
  - Transaction Type  

---

## Key Insights

- Majority of transactions are non-risky, with a smaller segment flagged for review.  
- UPI, Debit Card, Credit Card, and Net Banking are the most frequently used payment methods.  
- Risky transactions are spread across multiple cities.  
- Transactions from unknown devices or unknown locations may indicate suspicious behavior.  
- Users with previous fraudulent history require closer monitoring.  

---

## Business Impact

This dashboard can help financial institutions and payment platforms:

- Detect suspicious transactions faster  
- Monitor fraud trends in real time  
- Reduce operational and financial risk  
- Improve customer account security  
- Enable data-driven fraud prevention strategies  

---

## Dashboard Preview
![Dashboard Preview](Dashboard%20Preview.png)


## Data Source

This dataset was obtained from **Kaggle** and includes simulated transaction records used to analyze fraud patterns, risky transactions, and customer behavior.
