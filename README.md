# AI-Based Inventory Demand Forecasting & Stock Optimization

## 1. Project Overview

The **AI-Based Inventory Demand Forecasting and Stock Optimization** project uses Machine Learning to predict future product demand and recommend suitable inventory levels.

The project uses the Random Forest Regression algorithm to analyze historical sales data and forecast product demand.

Based on predicted demand, the system calculates safety stock, reorder points, and recommended stock quantities.

The main purpose is to reduce overstocking, prevent stock shortages, and improve inventory management.

## 2. Problem Statement

Businesses often face difficulties in maintaining appropriate inventory levels. Overstocking increases storage costs, while understocking can result in lost sales and dissatisfied customers.

This project provides an AI-based solution to forecast product demand and support better inventory planning.

## 3. Objectives

- Analyze historical inventory and sales data.
- Predict future product demand using Machine Learning.
- Identify demand patterns and trends.
- Calculate safety stock requirements.
- Determine reorder points.
- Recommend optimal inventory quantities.
- Reduce overstocking and stock shortages.

## 4. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Google Colab | Development environment |
| Pandas | Data manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning |
| Random Forest | Demand forecasting |
| Overleaf | Technical report preparation |
| GitHub | Project hosting |

## 5. Dataset Description

The project uses a CSV dataset named `inventory_dataset.csv`.

The dataset should contain the following columns:

| Column | Description |
|---|---|
| Date | Date of sales or demand |
| Product / Item | Product identification |
| Sales / Demand | Quantity sold or demanded |
| Store | Store identification (optional) |
| Promotion | Promotion indicator (optional) |
| Current Stock | Available inventory (optional) |

The program automatically identifies common column names. If your dataset uses different names, update the column mapping in the Python code.

## 6. Machine Learning Algorithm

### Random Forest Regression

Random Forest Regression is an ensemble Machine Learning algorithm that combines multiple decision trees to predict numerical values.

In this project, it is used to predict future product demand based on historical demand and date-related features.

### Model Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

## 7. Project Methodology

1. Upload the inventory dataset.
2. Perform data preprocessing.
3. Handle missing and duplicate values.
4. Perform Exploratory Data Analysis (EDA).
5. Create lag and rolling average features.
6. Split the dataset into training and testing data.
7. Train the Random Forest Regression model.
8. Predict future demand.
9. Evaluate model performance.
10. Calculate safety stock and reorder points.
11. Generate inventory recommendations.
12. Export graphs and CSV results.

## 8. Inventory Optimization Formulas

### Safety Stock

Safety stock provides additional inventory to protect against demand uncertainty.

`Safety Stock = Z × Standard Deviation of Daily Demand × √Lead Time`

### Reorder Point

`Reorder Point = (Average Daily Demand × Lead Time) + Safety Stock`

### Recommended Stock

`Recommended Stock = (Predicted Daily Demand × Planning Days) + Safety Stock`

The current implementation uses a 7-day lead time, a 30-day planning period, and a Z-score of 1.65.

## 9. Exploratory Data Analysis

The project generates the following visualizations:

1. Demand Distribution Histogram
2. Average Demand by Product
3. Daily Demand Trend
4. Monthly Demand Analysis
5. Correlation Heatmap
6. Day vs Demand Scatter Plot
7. Demand Outlier Boxplot
8. Actual vs Predicted Demand
9. Inventory Stock Optimization
10. Average Predicted Demand by Product

## 10. Project Output Files

The program generates the following CSV files:

- `demand_forecast_results.csv`
- `inventory_optimization_results.csv`
- `model_performance.csv`
- `cleaned_inventory_dataset.csv`
- `outlier_analysis.csv`

It also generates a Graphs folder containing all ten visualization images.

All results are collected in a ZIP file named:

`Inventory_Project_Complete_Results.zip`

## 11. How to Run the Project

1. Download or clone this GitHub repository.
2. Open Google Colab.
3. Create a new notebook.
4. Paste the project Python code.
5. Upload `inventory_dataset.csv` when prompted.
6. Run the code.
7. View the generated graphs and model evaluation results.
8. Download the CSV files and ZIP folder.

## 12. Installation

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Google Colab already provides most of these libraries.

## 13. Future Scope

- Integration with real-time sales data.
- Development of an interactive inventory dashboard.
- Implementation of advanced forecasting algorithms such as LSTM.
- Automated purchase order generation.
- Integration with supplier and warehouse systems.
- Product pricing and seasonal demand analysis.

## 14. Conclusion

This project demonstrates how Artificial Intelligence and Machine Learning can improve inventory management.

The Random Forest Regression model predicts product demand using historical data. The system then calculates safety stock, reorder points, and recommended inventory quantities.

It helps businesses make data-driven inventory decisions, improve stock planning, and reduce unnecessary inventory costs.

## 15. References

- Scikit-learn: https://scikit-learn.org/
- Pandas: https://pandas.pydata.org/
- NumPy: https://numpy.org/
- Matplotlib: https://matplotlib.org/
- Seaborn: https://seaborn.pydata.org/
- Google Colab: https://colab.research.google.com/
- Overleaf: https://www.overleaf.com/

---

**Project Title:** AI-Based Inventory Demand Forecasting & Stock Optimization

**Algorithm:** Random Forest Regression

**Programming Language:** Python

**Dataset:** inventory_dataset.csv
