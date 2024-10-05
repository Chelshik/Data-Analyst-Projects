# Financial Analysis Project Documentation

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Collection](#data-collection)
3. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Financial Ratio Analysis](#financial-ratio-analysis)
6. [Trend Analysis](#trend-analysis)
7. [Cash Flow Analysis](#cash-flow-analysis)
8. [Employee and Inflation Impact Analysis](#employee-and-inflation-impact-analysis)
9. [Predictive Modeling](#predictive-modeling)
10. [Conclusion](#conclusion)

## Project Overview
The goal of this project is to conduct a comprehensive financial analysis of ten companies over a specified period. The analysis includes exploratory data analysis, financial ratio analysis, trend analysis, DuPont analysis, cash flow analysis, and predictive modeling to forecast future financial metrics.

## Data Collection
The dataset comprises historical financial data from ten companies, including the following key columns:
- `year`
- `company`
- `category`
- `market cap (in b USD)`
- `revenue`
- `net income`
- `roe` (Return on Equity)
- `current ratio`
- `debt/equity ratio`
- `cash flow from operating`
- `number of employees`
- `inflation rate (in US)`

## Data Cleaning and Preprocessing
The data was cleaned to ensure consistency and correctness:
- Removed duplicates and irrelevant columns.
- Handled missing values where necessary.
- Converted categorical columns to numerical values using Label Encoding.

## Exploratory Data Analysis (EDA)
In this phase, we summarized the dataset and visualized key metrics:
- Analyzed unique values in critical columns (e.g., `company`, `category`).
- Visualized important financial metrics such as `market cap`, `revenue`, and `net income` for each company over the years.

## Financial Ratio Analysis
We analyzed various financial ratios to assess company health:
- **Profitability Ratios:** ROE, Net Profit Margin
- **Liquidity Ratios:** Current Ratio
- **Solvency Ratios:** Debt/Equity Ratio

Visualizations were created to illustrate these metrics for comparative analysis across companies.

## Trend Analysis
Trend analysis was conducted for each company to observe the performance of key financial metrics (revenue, net income, and more) over the years. Line graphs illustrated these trends clearly.

## DuPont Analysis
The DuPont analysis was performed for each company to break down ROE into its components, evaluating how effectively each company uses its assets and equity to generate profit.

## Cash Flow Analysis
Cash flow analysis included visualizations of:
- Cash flow from operating activities
- Cash flow from investing activities
- Cash flow from financial activities

Each company's cash flow metrics were visualized over the years to assess liquidity and financial health.

## Employee and Inflation Impact Analysis
We examined the impact of employee count and inflation on financial performance metrics, visualizing these relationships to understand how they affect company outcomes.

## Predictive Modeling
A regression-based model was developed to forecast future financial metrics, such as revenue. The model was trained and tested using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

Label encoding was applied to the `company` variable to facilitate the regression analysis.

## Conclusion
This project provided valuable insights into the financial health and performance of the analyzed companies. The various analyses conducted, including financial ratio assessments, trend analysis, and predictive modeling, demonstrate the importance of historical financial data in making informed business decisions. The predictive model also shows promise in forecasting future performance based on historical trends.

### Future Work
Future work could include deeper dives into industry comparisons, advanced predictive modeling techniques, and incorporating additional financial metrics for a more robust analysis.

