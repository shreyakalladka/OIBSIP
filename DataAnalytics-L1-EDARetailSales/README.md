# Retail Sales Data Analysis

## Overview

This project performs **Exploratory Data Analysis (EDA)** on a retail sales dataset using Python. The analysis focuses on understanding sales patterns, customer information, product categories, and relationships between numerical variables.

The dataset contains **1,000 transactions and 9 columns**, including transaction details, customer information, product category, quantity, price, and total amount.

## Objectives

* Explore and understand the retail sales dataset
* Check the structure and quality of the data
* Calculate descriptive statistics
* Analyze monthly sales trends
* Analyze revenue by product category
* Identify correlations between numerical variables using a heatmap

## Dataset

The dataset contains the following columns:

* **Transaction ID** – Unique transaction identifier
* **Date** – Date of the transaction
* **Customer ID** – Unique customer identifier
* **Gender** – Customer gender
* **Age** – Customer age
* **Product Category** – Category of the purchased product
* **Quantity** – Number of units purchased
* **Price per Unit** – Price of one unit
* **Total Amount** – Total transaction amount

The dataset contains no missing values in the analyzed columns.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Analysis Performed

### 1. Data Exploration

* Loaded the dataset using Pandas
* Examined the first few records
* Checked dataset shape and information
* Checked for missing values
* Generated descriptive statistics

### 2. Descriptive Statistics

Calculated:

* Mean
* Median
* Mode
* Standard deviation

for the numerical variables in the dataset.

### 3. Time Series Analysis

The `Date` column was converted into a datetime format and monthly sales were analyzed using the `Total Amount` column.

### 4. Revenue by Product Category

Revenue was grouped by **Product Category** using the total transaction amount and visualized using a bar chart.

### 5. Correlation Heatmap

A correlation matrix was created for numerical variables and visualized using a heatmap to understand relationships between the variables.

## Key Dataset Statistics

* Total transactions: **1,000**
* Average age: **41.39 years**
* Average quantity per transaction: **2.51**
* Average price per unit: **179.89**
* Average transaction amount: **456**
* Age range: **18–64 years**
* Quantity range: **1–4**
* Total amount range: **25–2,000**

## Conclusion

The project provides an overview of retail sales data through data exploration, statistical analysis, sales trend analysis, category-wise revenue analysis, and correlation analysis. These techniques help in understanding customer transactions and overall sales patterns.

## Project File

* `L1_Task1.ipynb` – Google Colab/Jupyter Notebook containing the complete analysis
* `retail_sales_dataset.csv` – Dataset used for the analysis
