# Power BI Sales Forecasting Dashboard

## 📊 Project Overview

This project showcases an interactive Power BI dashboard created to analyze and forecast sales data.The objective of this dashboard is to demonstrate how the integration of Power BI can enhance decision-making, uncover regional trends, identify top-performing products, and predict future sales using advanced analytics.

---

## 🧾 Dataset Overview

- **File Used**: `IT_Sales_Data_5Y_Forecasting.xlsx`
- **Rows**: ~350
- **Columns**: 15+ including:
  - `Date`, `Year`, `Month`, `Region`, `Client Name`, `Sales Rep`
  - `Product Category`, `License Fee`, `Customization Fee`, `Maintenance Fee`
  - `Total Sale Amount`, `Cost`, `Profit`, `Project Duration (Days)`
  - `Payment Status`, `Future Potential`

This dataset covers sales transactions from **2020 to 2024**, categorized by product type, region, client, and profitability.

---

## 📈 Power BI Dashboard Features

The Power BI file (`Sales data.pbix`) includes the following dashboards and analyses:

### 1. **Sales Overview Dashboard**
- **Total Sales & Profit KPIs**: Highlights overall sales revenue and profit.
- **Monthly Sales Trend (Line Chart)**: Shows fluctuations in sales across months for each year.


### 2. **Forecasting Dashboard**
- **Built-in Time Series Forecast (Line Chart with Forecast)**:
  - Uses Power BI’s built-in forecasting tool to project sales from 2023 to 2025.
  - Highlights seasonal trends and future potential.
- **Linear Regression Forecast (DAX Model)**:
  - Implements a custom measure using DAX to predict future `Total Sales`.
  - Shows trend lines to compare actual vs predicted values.


---

## 🔮 Forecasting Techniques Used

1. **Built-in Forecast (Power BI Analytics Panel)**:
   - Used for time-series forecasting based on historical `Total Sale Amount`.

2. **Moving Average Trend Line**:
   - 3-month and 6-month moving averages applied to visualize short-term trends.

3. **Linear Regression (via DAX)**:
   - Custom forecast using regression model equation built with DAX expressions.

4. **Region-wise Forecast Comparison**:
   - Helps identify which locations have the best future outlook.

5. **Actual vs Forecasted Comparison**:
   - Separate page compares actual sales from 2023–2024 against predictions made from 2022 data.

---

## 🛠 Tools Used

- **Power BI Desktop**
- **Microsoft Excel**
- **DAX (Data Analysis Expressions)**

---

## ✅ Key Insights

- The company saw a steady increase in software solution sales in the southern region (Chennai) over the years.
- Support Services is the most profitable category.
- Pending and Overdue payments contribute significantly to cash flow issues.
- Forecasting models indicate strong growth potential in 2025 if trends continue.
- High-Future-Potential clients contribute to 60% of upcoming forecasted revenue.

---

## 👨‍🎓 Academic Use

This dashboard is part of an MBA final year project titled:
> **"A Study of Integration of Power BI in Sales Forecasting"**
