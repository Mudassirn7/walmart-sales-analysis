# Walmart Sales Analysis & Forecasting

This repository contains a comprehensive analysis of **Walmart weekly sales**, including data cleaning, exploratory data analysis (EDA), statistical testing, regression modeling, SARIMA forecasting, and actionable business insights.

## Overview

The notebook includes:

- **Data Cleaning & Preprocessing:** Handling missing values, outliers, and formatting dates.  
- **Exploratory Data Analysis (EDA):**  
  - Total weekly sales over time  
  - Sales by store  
  - Holiday vs non-holiday sales  
  - Correlation heatmaps  
- **Statistical Analysis:**  
  - Descriptive statistics of `Weekly_Sales`  
  - T-test for holiday vs non-holiday weeks  
  - Feature correlations  
- **Regression Modeling:** Linear regression using features like `CPI`, `Fuel_Price`, `Temperature`, `Unemployment`, `Holiday_Flag`, and `Store`.  
- **SARIMA Forecasting:** Predicting future weekly sales trends.  
- **Business Insights & Recommendations:** Key drivers of sales, effects of holidays and economic indicators, and actionable strategies for inventory and promotions.

## Dataset

- Original dataset: [Walmart Sales Dataset by Mikhail1681](https://www.kaggle.com/datasets/mikhail1681/walmart-sales)  
- Kaggle notebook dataset used in analysis: [Walmart Sales Analysis & Forecasting with Python](https://www.kaggle.com/code/muhammadmudassir07/walmart-sales-analysis-forecasting-with-python)

## Key Findings

- **Top Stores:** Stores 2, 4, 13, 14, and 20 are the highest performers.  
- **Holiday Effect:** Significant increase in sales during holidays (**T = 2.68, P = 0.008**).  
- **Economic Factors:** CPI, Fuel_Price, and Unemployment negatively affect sales.  
- **Forecasting:** SARIMA model predicts upcoming trends to support inventory planning.

## How to View

- View the **interactive notebook on Kaggle**: [Click Here](https://www.kaggle.com/code/muhammadmudassir07/walmart-sales-analysis-forecasting-with-python)  
- Or explore the `.ipynb` notebook directly in this repository.

## Recommendations

- Increase inventory and promotions during holidays to meet demand spikes.  
- Focus marketing and operational resources on top-performing stores while identifying growth opportunities in lower-performing stores.  
- Monitor CPI and unemployment trends to anticipate potential dips in sales.  
- Consider targeted delivery options if fuel prices rise to maintain customer traffic.
