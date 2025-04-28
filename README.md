## Background

![main](/Picture/code.png)

Python script to download file using Kaggle API, [link](/python_and_junyper/kaggle_download.py)
To access the original file, please refer to this [link](/thedevastator/unlock-profits-with-e-commerce-sales-data/versions/2/Amazon%20Sale%20Report.csv)

# E-Commerce Sales Analysis Project

## Overview

In this project, I analyze e-commerce sales data from a CSV file, focusing on trends in product sales across various categories, cities, and states. The project also highlights B2B (Business-to-Business) sales performance to provide actionable insights. Using tools such as **Pandas**, **Numpy**, and **Matplotlib** in Python, the goal is to uncover significant patterns in sales and provide data-driven recommendations.

## Background

The e-commerce industry is highly competitive, and understanding sales patterns is crucial for businesses to optimize their strategies. By analyzing the sales data, businesses can identify which products are performing well, which regions have high demand, and how B2B sales compare to B2C sales. This project helps demonstrate the ability to manipulate, visualize, and derive insights from complex datasets.

## Results

To fast forward to results, please refer to this [link](/python_and_junyper/analysis.ipynb)

## Tools Used

- **Python**
  - **Pandas**: For data manipulation and analysis.
  - **Numpy**: For numerical operations and data handling.
  - **Matplotlib**: For creating visualizations (e.g., bar charts, line graphs, etc.).
  - **Jupyter Notebook**: For interactive data analysis.

- **Libraries**: 
  - `pandas`
  - `numpy`
  - `matplotlib.pyplot`

## Data Description

The dataset contains sales data for various e-commerce transactions, with the following columns:

- `Order ID`: Unique identifier for each order.
- `Product`: Name of the product sold.
- `Category`: Product category (e.g., blouse, dress, etc.).
- `Quantity Sold`: Number of units sold.
- `Sales`: Total sales revenue for the transaction.
- `City`: City where the sale took place.
- `State`: State where the sale took place.
- `Customer Type`: B2B (Business-to-Business) or B2C (Business-to-Consumer).
- `Date`: Date of the transaction.

## Project Goals

1. **Data Cleaning**: Prepare the dataset by handling missing values, outliers, and data types.
2. **Exploratory Data Analysis (EDA)**:
   - Identify top-performing products and categories.
   - Examine trends in sales across different cities and states.
   - Analyze the performance of B2B vs B2C sales.
3. **Visualizations**:
   - Create various plots to visualize sales trends, top products, and B2B vs B2C comparisons.
4. **Insights and Recommendations**: Draw actionable insights from the analysis and suggest strategies for improving sales performance.

## Steps Taken

1. **Data Import and Cleaning**:
   - Loaded the dataset from the provided CSV file using **Pandas**.
   - Cleaned the data by handling missing values and standardizing columns.

2. **Exploratory Data Analysis**:
   - Used **Pandas** to perform aggregations, such as total sales by category, city, and state.
   - Calculated metrics like total revenue, average order value, and quantity sold per category.

3. **B2B vs B2C Sales Analysis**:
   - Filtered the dataset based on customer type (B2B vs B2C).
   - Compared the performance of B2B vs B2C sales through visualizations.

4. **Visualizations**:
   - Created visualizations such as bar charts, pie charts, and line graphs to showcase:
     - Sales trends across cities and states.
     - The distribution of product sales by category.
     - B2B vs B2C sales performance.

## Insights & Conclusions

- **Top-performing Categories**: Categories like electronics and clothing showed high sales volumes and revenue.
- **Geographic Insights**: Cities and states with higher population densities tend to generate higher sales.
- **B2B vs B2C**: B2B sales accounted for a significant portion of overall revenue, especially in high-value product categories.
- **Actionable Recommendations**:
  - Focus on expanding product categories with higher sales potential.
  - Target high-performing regions for localized marketing strategies.
  - Enhance B2B offerings to capture a larger share of the business market.

## Challenges and Lessons Learned

- Handling missing or incorrect data in large datasets was a challenge that required careful cleaning.
- Visualizing complex data patterns (e.g., B2B vs B2C sales) required appropriate aggregation techniques.
- Gaining a deep understanding of sales trends helped to make better recommendations for the business.

## Future Work

- Integrate machine learning models to predict future sales based on historical data.
- Analyze the impact of pricing strategies on sales performance.
- Build a dashboard for interactive visualizations and real-time data analysis.

## Conclusion

This project demonstrates the ability to manipulate and analyze e-commerce sales data using Python. By uncovering valuable trends and providing actionable insights, it serves as a foundation for strategic decision-making in the e-commerce industry.

## Dataset

You can download the dataset from [Kaggle: Unlock Profits with E-Commerce Sales Data](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data/data).

