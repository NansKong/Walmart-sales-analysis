
# Walmart Sales Data Analysis

This project presents a complete data analysis pipeline using Walmart's retail transaction data. It includes **data preprocessing**, **feature engineering**, and **exploratory data analysis (EDA)** to uncover meaningful insights about customer behavior, product performance, and overall business trends.

---

## Dataset Overview

- **Source**: [Walmart 10K Sales Dataset (Kaggle)](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)
- **Files**:
  - `Walmart_Sales_Data.csv` – Raw transactional data
  - `Walmart_cleaned_Sales_Data.csv` – Cleaned and processed dataset

---

## Tools & Technologies

- **Python** (Jupyter Notebook)
- **MySQL** (Relational Database)
- **Libraries**:  
  `pandas`, `matplotlib`, `seaborn`, `mysql-connector-python`

---

## Project Workflow

### 🔹1. Data Loading
- Loaded raw CSV into a pandas DataFrame
- Set up MySQL database `st_project_1` and created table `walmart_dataset`
- Inserted data from the DataFrame into MySQL using Python

### 🔹2. Data Cleaning
- Removed currency symbols and formatted numerical columns
- Converted `Date` and `Time` columns to proper `datetime` types
- Dropped **31 rows** with missing `unit_price` or `quantity`
- Verified data types, null values, and checked for duplicates

### 🔹3. Feature Engineering
- Created new column:
  ```
  total_amount = unit_price * quantity
  ```
- Exported the cleaned dataset as `Walmart_cleaned_Sales_Data.csv`

### 🔹4. Exploratory Data Analysis (EDA)
Used `matplotlib` and `seaborn` to analyze and visualize:
- Revenue and quantity sold by:
  - Branch
  - Product Category
  - City
  - Hour of Day
  - Payment Method
- Average profit margins by:
  - Branch
  - Category

---

## Key Insights

- **Branch B** had the highest overall revenue.
- **Electronic Accessories** and **Food & Beverages** were the most sold categories.
- Customer traffic peaked between **1 PM – 3 PM**.
- **Credit cards** were the most common payment method.
- **Branch A** had the highest average profit margin.

---

## Included Files

| File Name                         | Description                               |
|----------------------------------|-------------------------------------------|
| `Walmart_Sales_Data.csv`         | Original dataset                          |
| `cleaned_sales_data.csv` | Cleaned dataset with new features         |
| `walmart_analysis.ipynb`         | Full notebook with cleaning + EDA         |
| `README.md`                      | Project summary and documentation         |

---

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/walmart-sales-analysis.git
   ```

2. **Install required libraries**
   ```bash
   pip install pandas matplotlib seaborn mysql-connector-python
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open and run** `walmart_analysis.ipynb`

---

## Learning Highlights

- How to clean and preprocess real-world sales data
- Load and query structured data using **MySQL**
- Perform detailed EDA and create visualizations
- Extract and summarize key business insights
- Organize and document a data project for GitHub
