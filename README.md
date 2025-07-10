# 📊 Walmart Sales Analysis
## 📝 Project Overview
This project focuses on analyzing Walmart sales data to find useful business insights. We use Python, MySQL, and Jupyter Notebook to clean, process, and explore the data.

🔧 Tools Used
  Python (Pandas, Matplotlib, Seaborn)
  MySQL (Database)
  Jupyter Notebook
  Git & GitHub

✅ Project Steps
1. Setup
  Create a MySQL database: st_project_1
  Create a table: walmart_dataset
  Load CSV data into the MySQL table using Python

2. Data Loading
  Read data using Pandas
  Connect to MySQL using mysql-connector-python
  Insert data into MySQL using executemany()

3. Data Cleaning
  Removed duplicates
  Handled missing values
  Fixed data types (dates, times, floats)
  Formatted currency fields
  Saved a cleaned version of the dataset

4. Feature Engineering
  Added a new column: total_amount = unit_price * quantity

5. Data Analysis (EDA)
  Revenue trends by branch and category
  Best-selling products
  Sales by city and payment method
  Peak sales times
  Profit margin analysis

6. Documentation & Publishing
  Added comments and Markdown in the notebook
  Shared the project on GitHub with raw and cleaned data

📦 Files Included
  Walmart_Sales_Data.csv (raw data)
  walmart_cleaned_dataset.csv (cleaned data)
  walmart_analysis.ipynb (analysis code)
  README.md (this file)
