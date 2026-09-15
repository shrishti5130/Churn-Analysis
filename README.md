# 📊 Customer Churn Analysis

## 📌 Project Overview

Customer churn is an important business problem because losing customers can directly affect revenue and growth.

This project analyzes customer data to understand customer behavior, identify patterns related to churn, and generate meaningful business insights.

The project follows a data analysis workflow including data loading, data cleaning, exploratory data analysis (EDA), and database analysis.

---

## 🎯 Objectives

- Understand customer churn behavior
- Clean and prepare the raw customer dataset
- Perform exploratory data analysis
- Identify important patterns and trends
- Analyze customer-related factors associated with churn
- Store and analyze data using a database
- Generate actionable business insights

---

## 📂 Dataset

The project uses customer churn data containing customer-related information and churn indicators.

### Dataset File

`customer_churn_data_raw.xlsx`

The dataset is loaded and analyzed using Python and Pandas.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Jupyter Notebook**
- **SQL**
- **SQLite**
- **Excel**
- **Data Cleaning**
- **Exploratory Data Analysis (EDA)**

---

## 🔄 Project Workflow

### 1. Data Loading

The raw Excel dataset is loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_excel("customer_churn_data_raw.xlsx")
