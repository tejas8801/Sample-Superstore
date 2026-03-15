# Sample-Superstore
An end-to-end exploratory data analysis (EDA) project using SQL and Python on the Superstore Sales dataset from Kaggle.

# Project Summary
In this project,
Downloaded real-world sales data from Kaggle using Kaggle API.
Cleaned and explored the dataset using pandas.
Stored and queried the data using SQLite directly inside Python.
Performed SQL queries to extract business insights.
Created beautiful visualizations using seaborn and matplotlib.
# Tools & Technologies
Python (pandas, sqlite3, seaborn, matplotlib)
SQL (SQLite)
Google Colab (Jupyter environment)
Kaggle API (for automated data download)
# Dataset
-<a href='https://github.com/tejas8801/Sample-Superstore/blob/main/Sample%20-%20Superstore.csv'>Sampledata</a>


# Project Workflow

1️. Download Dataset via Kaggle API
Automated download directly inside Google Colab.

2️. Load Data
Read the CSV file into pandas, handle encoding issues using latin1 encoding.
3.Explore Data
Checked column names, data types, missing values.
Generated summary statistics.

4️. Store Data in SQLite Database
Created a local SQLite database file (superstore.db).
Loaded the cleaned DataFrame into SQL table Orders.

5️. SQL Queries
Total Sales by Region
Top 5 Products by Sales
Total Sales per Category
Total Profit per Region
Monthly Sales Trends

6️. Visualizations
Created various charts to visualize business insights
Bar plots for sales and profits
Line plot for sales trends over time

# Visualizations
https://github.com/tejas8801/Sample-Superstore/blob/main/Screenshot%202026-03-16%20035150.png
https://github.com/tejas8801/Sample-Superstore/blob/main/Screenshot%202026-03-16%20035216.png
https://github.com/tejas8801/Sample-Superstore/blob/main/Screenshot%202026-03-16%20035230.png
https://github.com/tejas8801/Sample-Superstore/blob/main/Screenshot%202026-03-16%20035256.png

   
# Key Insights
Sales distribution across regions

Top-performing products

Profitability by region

Monthly sales fluctuations

# Future Scope

More advanced SQL queries (joins, subqueries)

Build a dashboard (e.g. using Streamlit)

Predictive modeling on sales trends
