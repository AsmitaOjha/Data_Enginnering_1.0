# Data Pipeline for Real-Time Stock Prices

## Overview
This project is a guided exercise designed to build a complete data engineering pipeline for real-time stock market data. Through this project, I learned how to extract data from a public API, clean and transform it into a usable format, store it in a PostgreSQL database, and visualize the data using Matplotlib. Finally, I automated the entire process using Python's scheduling libraries.

## What We Did

1. **Exploration of Alpha Vantage**
   - Learned about [Alpha Vantage](https://www.alphavantage.co/), a free API providing real-time stock market data.
   - Extracted stock data specifically for Apple using Alpha Vantage.

2. **Data Extraction and Cleaning**
   - Extracted raw data from the Alpha Vantage API.
   - Cleaned the data by converting the JSON dictionary into a Pandas DataFrame.
   - Converted the key representing the timestamp into the DataFrame index, with the remaining keys (open, high, low, close, volume) set as columns.

3. **Storing Data in PostgreSQL**
   - Established a connection to PostgreSQL.
   - Created a database called `stock_market_database`.
   - Within this database, created a table named `stock_data` to store the cleaned DataFrame.
   - Inserted the data into the table, ensuring that each record is uniquely identified by its timestamp.

4. **Data Visualization**
   - Utilized Matplotlib to create various visualizations:
     - **Trend Line:** Visualized stock prices over time to observe the overall trend.
     - **Histogram:** Plotted the distribution of closing prices.
     - **Moving Average Trend (Smoothing):** Applied a moving average to smooth out short-term fluctuations.
     - **Volatility Analysis:** Calculated the daily percentage change in closing prices to understand stock volatility.

5. **Automating the Data Pipeline**
   - Used Python's `schedule` and `time` libraries to automate the ETL (Extract, Transform, Load) process.
   - Scheduled the data pipeline to run at regular intervals (e.g., every 5 minutes) to continuously update the database with the latest stock data.

## Why We Did It
- **Hands-On Learning:** This project helped me gain practical experience in building a real-world data pipeline.
- **Real-Time Data Handling:** Learning how to work with live data sources, like Alpha Vantage, is essential in many data engineering roles.
- **Database Integration:** Storing and managing data in PostgreSQL is a critical skill for handling large datasets and performing analytics.
- **Data Visualization:** Visualizing data helps in understanding trends and patterns, which is vital for making data-driven decisions.
- **Automation:** Automating the ETL process ensures that the data remains current without manual intervention, which is key in production environments.

## Tools and Technologies
- **Python:** Programming language used for scripting the entire pipeline.
- **Alpha Vantage API:** Source for real-time stock market data.
- **Pandas:** Library for data manipulation and cleaning.
- **PostgreSQL:** Database for storing the cleaned stock data.
- **Matplotlib:** Library for visualizing the data.
- **Schedule & Time:** Python libraries for automating and scheduling the data pipeline.

## Conclusion
This guided project provided a comprehensive introduction to data engineering by covering the entire workflow—from data extraction and cleaning to storage, visualization, and automation. The skills learned here form a strong foundation for more advanced data engineering and data science projects.

*Project guided by ChatGPT's instructions.*

