<h1>Fraud Detection in Bank Transactions</h1>

<h2>Project Overview</h2>
This project focuses on detecting fraudulent transactions in bank data. The dataset was sourced from Kaggle (bank.xlsx). The steps involved include data loading, cleaning, exploration, anomaly detection, and visualization of suspicious patterns. The ultimate goal of this project is to identify suspicious users who might be involved in fraudulent activities.

<h3>Technologies Used</h3>
    1. Python
    2. Jupyter Notebook
    3. Pandas: Data manipulation
    4. Matplotlib: Data visualization
    5. Seaborn: Data visualization

<h3>Steps</h3>

###1. Data Collection
The dataset (bank.xlsx) was downloaded from Kaggle and used for analysis.
<br>
###2. Environment Setup
The necessary Python packages were installed, including Pandas, Matplotlib, and Seaborn for data analysis and visualization.<br>
###3. Data Loading and Exploration
The dataset was loaded and explored to understand its structure and identify any immediate patterns or issues.<br>
###4. Data Cleaning
Key steps in data cleaning included:
    Converting the date column to a proper date format.
    Converting all amounts to absolute values (to remove negative signs).<br>
###5. Basic Analysis of Transactions
Various analyses were performed to better understand the transaction data:
    A distribution of the balance amounts was visualized.
    The top 30 transaction types were listed using a bar chart.<br>
###6. Anomaly Detection
Several anomaly detection techniques were applied to the dataset:
    a. Large Transactions: Identified transactions above a certain threshold.
    b. Multiple Transactions in Short Time: Detected accounts with multiple transactions occurring within a short time span (e.g., within a week).
    c. Frequent Deposit/Withdrawal: Found users whose deposit/withdrawal patterns suddenly increased in frequency.
    d. Sudden Drop in Balance: Detected accounts with a sudden drop in balance by more than 80% in a single transaction.<br>
###7. Visualizing Fraud Patterns
Visualization techniques were used to display and understand fraudulent patterns:
    **Scatter Plot**: Compared fraudulent vs. normal withdrawals.
    **Top 10 Accounts with Most Rapid Transactions**: A bar plot of accounts with the highest number of rapid transactions.
    **Withdrawal Amount Over Time**: A line plot to visualize the withdrawal pattern of specific accounts over time.<br>
###8. Saving Suspicious Users
In the final step, suspicious users were saved in a CSV file for further investigation.<br>