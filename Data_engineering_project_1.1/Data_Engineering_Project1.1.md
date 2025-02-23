# Fraud Detection in Bank Transactions

## Project Overview
This project focuses on detecting fraudulent transactions in bank data. The dataset was sourced from Kaggle (`bank.xlsx`). The steps involved include data loading, cleaning, exploration, anomaly detection, and visualization of suspicious patterns. The ultimate goal of this project is to identify suspicious users who might be involved in fraudulent activities.

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas**: Data manipulation
- **Matplotlib**: Data visualization
- **Seaborn**: Data visualization

## Steps

### 1. Data Collection
The dataset (`bank.xlsx`) was downloaded from Kaggle and used for analysis.

### 2. Environment Setup
The necessary Python packages were installed, including Pandas, Matplotlib, and Seaborn for data analysis and visualization.

### 3. Data Loading and Exploration
The dataset was loaded and explored to understand its structure and identify any immediate patterns or issues.

### 4. Data Cleaning
Key steps in data cleaning included:
- Converting the date column to a proper date format.
- Converting all amounts to absolute values (to remove negative signs).

### 5. Basic Analysis of Transactions
Various analyses were performed to better understand the transaction data:
- A distribution of the balance amounts was visualized.
- The top 30 transaction types were listed using a bar chart.

### 6. Anomaly Detection
Several anomaly detection techniques were applied to the dataset:
- **Large Transactions**: Identified transactions above a certain threshold.
- **Multiple Transactions in Short Time**: Detected accounts with multiple transactions occurring within a short time span (e.g., within a week).
- **Frequent Deposit/Withdrawal**: Found users whose deposit/withdrawal patterns suddenly increased in frequency.
- **Sudden Drop in Balance**: Detected accounts with a sudden drop in balance by more than 80% in a single transaction.

### 7. Visualizing Fraud Patterns
Visualization techniques were used to display and understand fraudulent patterns:
- **Scatter Plot**: Compared fraudulent vs. normal withdrawals.
- **Top 10 Accounts with Most Rapid Transactions**: A bar plot of accounts with the highest number of rapid transactions.
- **Withdrawal Amount Over Time**: A line plot to visualize the withdrawal pattern of specific accounts over time.

### 8. Saving Suspicious Users
In the final step, suspicious users were saved in a CSV file for further investigation.
