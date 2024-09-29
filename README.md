# Walmart Store Performance Analysis

This project focuses on analyzing and forecasting Walmart store performance using historical sales data. By utilizing various data-driven techniques, we explore sales trends, visualize patterns, and apply machine learning models for forecasting future sales. This project leverages Python libraries like pandas, NumPy, Matplotlib, Seaborn, and others to process the data and gain insights.

## Project Overview

Walmart is a leading retailer generating vast amounts of sales data. This project aims to:
- Analyze historical data from Walmart stores.
- Visualize trends in sales and performance.
- Forecast future sales based on historical patterns using time series analysis.

### Key Features:
1. **Data Cleaning & Preprocessing**: Handle missing values, normalize the data, and prepare it for analysis.
2. **Exploratory Data Analysis (EDA)**: Visualize key trends and patterns using graphs and statistical summaries.
3. **Time Series Forecasting**: Implement forecasting models to predict future sales based on historical data.

## Dataset

The dataset used in this analysis is a CSV file containing Walmart sales data across multiple stores. It includes the following key columns:
- **Store**: Identifier for the store.
- **Date**: The date of sales.
- **Weekly_Sales**: Sales data for each week.
- **Holiday_Flag**: Indicator for whether the week includes a holiday (1 for holiday weeks, 0 otherwise).
- **Temperature**, **Fuel_Price**, **CPI**, **Unemployment**: External factors that could affect sales.

**Dataset Path**: 
- `Walmart Store Data.csv`

## Visualizations and Results

Several visualizations were generated to better understand the trends and relationships in the data. Here are some key visualizations and the insights they provided:

### 1. Weekly Sales Trend

![Weekly Sales Trend](Results/Average%20weekly%20sale%20per%20Store.png)

- **Description**: A line plot of weekly sales across all Walmart stores over time.
- **Insight**: The plot shows fluctuations in weekly sales, with visible peaks around holidays, indicating that holiday seasons play a significant role in driving higher sales.

### 2. Sales Distribution by Store

![Sales Distribution by Store](Results/Total%20Sale%20per%20Store.png)

- **Description**: A bar chart depicting total sales for each store.
- **Insight**: Certain stores consistently outperform others, indicating potential factors like store location, management, or customer base that could explain this variation in performance.

### 3. Impact of Holidays on Sales

![Impact of Holidays on Sales](Results/Average%20sales%20during%20Holidays%20vs%20Non-Holidays.png)

- **Description**: A box plot comparing weekly sales during holiday weeks vs non-holiday weeks.
- **Insight**: The median sales during holiday weeks are significantly higher than non-holiday weeks. This confirms that holidays have a positive impact on store sales.

### 4. Correlation Matrix

![Correlation Matrix](Results/Correlation%20Matrix.png)

- **Description**: A heatmap showing the correlation between various features such as sales, temperature, unemployment, and other factors.

# Sales and Temperature

- **Description**: A scatter plot showing the relationship between sales and temperature.
- **Insight**: There is a weak but noticeable correlation between temperature and sales, suggesting that weather conditions may have a mild impact on consumer behavior.

# Unemployment Rate vs Sales

- **Description**: A scatter plot of weekly sales against the unemployment rate.
- **Insight**: As the unemployment rate increases, weekly sales tend to decrease slightly, indicating that economic conditions such as employment rates can influence consumer spending.

## Conclusion

This project demonstrates the power of data analysis and visualization in understanding Walmart store performance. The insights drawn from the data can help stakeholders make informed decisions to optimize sales strategies and improve overall performance.
