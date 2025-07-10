# Walmart-sales-analysis

Project Name: Walmart Data Analysis:
Project Overview
This project is an end-to-end data analysis solution designed to extract critical business
insights from Walmart sales data. We need to use Python for data processing and analysis,
MySQL as the database. The project is ideal for data analysts looking to develop skills in data
manipulation, SQL querying, and data pipeline creation.


Project Steps
1. Set Up the Environment
• Tools Used: Jupyter Notebook, Python, SQL (MySQL)
• Goal: Create a structured workspace within Jupyter and organize project folders for
smooth development and data handling.
2. Download Walmart Sales Data
• Data Source: Download the Walmart sales datasets from Kaggle.
• Dataset Link: Walmart Sales Dataset
• Storage: Save the data in the data/ folder for easy reference and access.
4. Install Required Libraries and Load Data
• Libraries: Install necessary Python libraries using:
• Loading Data in MYSQL: Create a database named ‘st_project_1’. Create a table
named ‘walmart_dataset’, with column names matching and mapping the columns in
csv file. Populate the table using the data from csv file.
• Load Data in Python: Create a connection, Python with MySQL Database. Load the
dataset in using Pandas DataFrame.
5. Explore the Data
• Goal: Conduct an initial data exploration to understand data distribution, check
column names, types, and identify potential issues.
• Analysis: Use functions like .info(), .describe(), and .head() to get a quick overview of
the data structure and statistics.
6. Data Cleaning
• Remove Duplicates: Identify and remove duplicate entries to avoid skewed results.
• Handle Missing Values: Drop rows or columns with missing values if they are
insignificant; fill values where essential.
• Fix Data Types: Ensure all columns have consistent data types (e.g., dates
as datetime, prices as float).
• Currency Formatting: Use .replace() to handle and format currency values for
analysis.
• Validation: Check for any remaining inconsistencies and verify the cleaned data.
7. Feature Engineering
• Create New Columns: Calculate the Total Amount for each transaction by
multiplying unit_price by quantity and adding this as a new column.
• Enhance Dataset: Adding this calculated field will streamline further SQL analysis and
aggregation tasks.
• Save the cleaned dataset: Save the cleaned dataset by the name
‘walmart_cleaned_dataset’.
8. EDA: Statistical Analysis and Visualization
• Trend Analysis:
o Revenue trends across branches and categories.
o Identifying best-selling product categories.
o Sales performance by time, city, and payment method.
o Analyzing peak sales periods and customer buying patterns.
o Profit margin analysis by branch and category.
• Code Optimization & Documentation: Write clean and well-documented code using
Markdown and Python comments.
9. Project Publishing and Documentation
• Documentation: Maintain well-structured documentation of the entire process in
Markdown or a Jupyter Notebook.
• Project Publishing: Publish the completed project on GitHub:
o The README.md file (this document).
o Jupyter Notebooks (if applicable).
o Dataset (Both raw and cleaned).
