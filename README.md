# Diwali Sales Data Analysis

**Google Colab Link:** https://drive.google.com/file/d/1Vbhxx_-Um847o8aK9jqWnNltPNRwfbyP/view?usp=sharing

This notebook analyzes Diwali sales data to identify key trends and insights.

## Data

The dataset used in this notebook is named `Diwali Sales Data.csv`. It contains information about customer purchases during the Diwali festival, including details such as User ID, Customer Name, Product ID, Gender, Age Group, Age, Marital Status, State, Zone, Occupation, Product Category, Orders, Amount, Status, and unnamed1.

## Analysis

The notebook performs the following analysis:

1. **Data Loading and Cleaning:** The data is loaded into a pandas DataFrame, and irrelevant columns (`Status` and `unnamed1`) are dropped. Missing values in the `Amount` column are removed, and the data type of the `Amount` column is converted to integer.
2. **Exploratory Data Analysis (EDA):** The notebook explores the data to understand the distribution of various features and their relationship with sales. This includes analyzing:
    - Gender vs. Sales Amount
    - Age Group vs. Sales Amount
    - State vs. Orders and Sales Amount
    - Marital Status vs. Sales Amount
    - Occupation vs. Sales Amount
    - Product Category vs. Sales Amount
    - Top 10 most sold products
3. **Visualization:** Various plots (count plots and bar plots) are generated using seaborn and matplotlib to visualize the findings from the EDA.

## Key Findings

The analysis reveals several key insights, including:

- Most buyers are females, and their purchasing power is greater than men.
- The majority of buyers are in the age group between 26 and 35 years, particularly females.
- Uttar Pradesh, Maharashtra, and Karnataka are the top states in terms of both orders and sales amount.
- Married women have a higher purchasing power.
- Buyers working in IT, Healthcare, and Aviation sectors are more likely to make purchases.
- Food, Clothing, and Electronics are the top-selling product categories.

Based on these findings, it can be concluded that married women in the age group 26-35 years from UP, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are more likely to buy products from the Food, Clothing, and Electronics categories during Diwali.

## How to run the notebook

1. **Clone the repository:** If the notebook is part of a repository, clone it to your local machine.
2. **Install dependencies:** Make sure you have the necessary libraries installed. You can install them using pip:
