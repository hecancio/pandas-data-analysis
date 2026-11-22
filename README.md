# Retail Sales Analysis

## Overview

This project explores a sample retail sales dataset using Python and Pandas. The goal is to perform an exploratory data analysis (EDA), identify sales trends, and extract useful business insights from the data.

The analysis is developed in a Jupyter Notebook and focuses on revenue, product performance, and regional sales.

## Dataset

The dataset contains 18 sample transactions covering four products and four regions.

The main variables include:

- **Date:** Transaction date.
- **Product:** Product sold.
- **Category:** Product category.
- **Region:** Sales region.
- **Units:** Number of units sold.
- **UnitPrice:** Price per unit.
- **Discount:** Discount applied to the transaction.

The dataset is synthetic and was created for learning and practicing data analysis techniques. No external files are required, as the data is included directly in the notebook.

## Tools and Libraries

- Python
- Pandas
- Jupyter Notebook

## Analysis

The notebook is organized into the following sections:

1. **General Overview:** Dataset structure, data types, descriptive statistics, and number of unique values.
2. **Revenue Analysis:** Calculation of total and average revenue, as well as identification of the highest-value transaction.
3. **Product Performance:** Comparison of products based on sales volume and generated revenue.
4. **Regional Analysis:** Revenue distribution across regions and analysis of average discounts.
5. **Business Insights:** Interpretation of the results and identification of relevant business patterns.

## Key Findings

- **Laptops** generate the highest total revenue (€7,298.00), despite having the lowest sales volume among the four products.
- **Mice** are the best-selling product in terms of units (55), but contribute considerably less to total revenue.
- The **North region** generates the highest revenue (€5,530.00), accounting for approximately 42.6% of total sales.
- Overall, the results suggest that revenue is influenced more by product value than by sales volume.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/hecancio/pandas-data-analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install pandas jupyter
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `retail_sales_analysis.ipynb` and run the cells.

## Project Purpose

This project was developed to practice data analysis with Pandas, including data inspection, data manipulation, aggregation, and interpretation of results. It also demonstrates how exploratory data analysis can be used to extract meaningful insights from a dataset.
