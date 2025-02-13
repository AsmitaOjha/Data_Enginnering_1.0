<h1>Wealth Data Analysis Project</h1>

<h2>Project Overview</h2>
This project is a guided practice from a YouTube series by Darshil Parmar. The project focuses on learning about data models, databases, and performing data cleaning and manipulation using pandas and PostgreSQL. I worked with a dataset related to wealth, followed various steps to clean the data, and set up a PostgreSQL database to insert and store the cleaned data.

<h3>What I Learned</h3>

<h3>1. Data Modeling and Databases:</h3>
Gained an understanding of how data is structured in databases and how to work with tables.
Learned the basics of relational databases and how to design tables to hold structured data.

<h3>2. Tools Used:</h3>
Jupyter Notebook: For writing and executing Python code.
PostgreSQL: As the relational database system.
Pandas: For data manipulation and cleaning.
Psycopg2: A Python library for connecting to PostgreSQL databases.

<h3>3. Steps Involved in the Project</h3>
    **a. Dataset:**
    I used a dataset with 3 CSV files containing data related to wealth. These files were provided in the project instructions.
    **b. Data Preparation:**
    I created pandas DataFrames by reading the CSV files, focusing only on the columns relevant to my analysis.
    **c. Data Cleaning:**
    Used pandas to clean the dataset by removing any rows containing null values, ensuring the dataset was ready for insertion into the database.
    **d. Connecting Python to PostgreSQL:**
    Installed the psycopg2 library to enable the connection between pandas and the PostgreSQL database.
    **e. Database Creation:**
    From within Jupyter Notebook, I created a new database called accounts in PostgreSQL.
    **f. Creating Tables:**
    I created 3 tables inside the accounts database. Each table was based on one of the DataFrames created from the CSV files.
    **g. Inserting Data:**
    I inserted data row by row from each of the 3 DataFrames into their respective tables in the PostgreSQL database.
    **h. Committing Changes:**
    After inserting all data, I committed the changes to make sure the data was permanently saved in the database.

<h3>4. Tools and Technologies</h3>
    Python: Used for data manipulation and interaction with PostgreSQL.
    Pandas: For working with CSV files and cleaning the data.
    PostgreSQL: The relational database where the cleaned data was stored.
    psycopg2: A Python library used to connect and interact with PostgreSQL.
    Jupyter Notebook: Used for writing and running Python code in an interactive environment.

This project was completed by following the YouTube videos from Darshil Parmar's channel, which provided the guidance for each step. The videos explained how to work with PostgreSQL and pandas and build a complete end-to-end project.



