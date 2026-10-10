# Supermarket Sales Analysis

### Exploratory Data Analysis | Python | Pandas | Seaborn | Matplotlib

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a supermarket sales dataset to understand sales performance, customer spending behaviour, product category trends, and transaction patterns.

The analysis includes data quality assessment, cleaning, univariate, bivariate, and multivariate exploration, followed by business insights.

## Dataset

- **Records:** 1,000 transactions
- **Original Features:** 17
- **Cleaned Features:** 20
- **Branches:** A, B, C
- **Product Categories:** 6
- **Source:** Supermarket Sales Dataset

The dataset includes transaction details, product categories, customer information, payment methods, sales amounts, and customer ratings.

## Tools and Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Analysis Performed

1. **Dataset Understanding:** Examined dataset structure, data types, and variable roles.
2. **Data Quality Assessment:** Checked missing values, duplicates, categorical inconsistencies, invalid values, and outliers.
3. **Data Cleaning:** Converted date/time formats, retained valid outliers, and created Hour, Weekday, and Month features.
4. **Univariate EDA:** Analyzed numerical distributions and categorical frequencies.
5. **Bivariate EDA:** Investigated relationships between sales, quantities, branches, product categories, and payment methods.
6. **Multivariate EDA:** Explored customer spending and product-line performance across branches.
7. **Business Analysis:** Examined revenue contribution, branch performance, customer behaviour, temporal sales trends, and customer ratings.

## Key Findings

- **Top Revenue Category:** Food and beverages generated the highest revenue (56,144.84).
- **Branch Performance:** Branch C recorded the highest total sales (110,568.71).
- **Customer Spending:** Members had slightly higher average transaction values than Normal customers.
- **Peak Sales Activity:** Revenue peaked at 7 PM, while Saturday recorded the highest weekday revenue.
- **Customer Ratings:** Ratings showed weak relationships with price, quantity, and transaction value.

## Data Cleaning Summary

The dataset contained no missing values or duplicate transactions. Nine potential high-value outliers were retained because they represented mathematically consistent transactions.

Three derived features—Hour, Weekday, and Month—were added for temporal analysis.

The cleaned dataset contains **1,000 rows and 20 columns**.

## Conclusion

The analysis highlights variations in sales across product categories, branches, and time periods. While some customer groups and branches show higher average transaction values, many differences are small relative to transaction variability.

The cleaned dataset and findings provide a foundation for further statistical analysis and predictive modelling.

## Author

**Zainab Saad**  
BS Computer Science | FAST-NUCES  
