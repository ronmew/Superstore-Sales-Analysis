# Superstore Sales Analysis

## Project Overview

This project focuses on data cleaning, exploratory data analysis (EDA),
and visualization of the Superstore sales dataset using Python.

The objective is to identify important patterns in sales, profit,
products, regions, discounts, and yearly performance.

## Objectives

- Understand the dataset
- Check and clean data quality
- Detect potential outliers
- Analyze sales and profit
- Identify important business patterns
- Create meaningful visualizations
- Generate business insights

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Potential outliers
- Invalid numerical values
- Date inconsistencies

No missing values or duplicate records were found.

The `Order Date` and `Ship Date` columns were converted to datetime format.

A `Shipping Days` feature was created to analyze shipping duration.

## Exploratory Data Analysis

The project includes:

- Sales distribution
- Profit distribution
- Sales by category
- Sales by region
- Profit by sub-category
- Customer segment analysis
- Yearly sales trend
- Discount vs Profit analysis
- Correlation heatmap

## Key Insights

- Technology is the highest-selling product category.
- Technology also generates the highest total profit.
- Phones and Chairs are among the highest-selling sub-categories.
- Copiers generate the highest total profit among the sub-categories.
- Tables generate substantial sales but have negative total profit.
- The West region has the highest total sales.
- 2017 recorded the highest annual sales.
- Discount has a weak negative relationship with profit.
- Sales and profit have a moderate positive relationship.

## Project Files

- `Superstore_Sales_Analysis.ipynb` — Complete analysis notebook
- `requirements.txt` — Required Python libraries

## Dataset

The Superstore dataset was obtained from Kaggle and used for educational
and analytical purposes.

## Conclusion

The project demonstrates how data cleaning, exploratory data analysis,
and visualization can transform raw transactional data into meaningful
business insights.
