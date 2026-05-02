# Prediction-of-Product-Sales

## Overview
This project explores a sales prediction dataset. The goal is to understand the data and identify patterns that influence product sales.

## Data Cleaning
- Handled missing values
- Fixed inconsistent categories
- Checked duplicates
- Reviewed data types

## Visualizations

### Histogram
The histogram shows the distribution of Item_Outlet_Sales.

### Heatmap
The heatmap shows the correlation between numerical features.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Model Explainability

### Linear Regression Coefficients
The Linear Regression model helps us understand how each feature affects sales. The most influential features were `Item_MRP`, `Outlet_Type_Grocery Store`, and `Outlet_Type_Supermarket Type3`.

`Item_MRP` has a strong positive effect, meaning higher product prices are associated with higher predicted sales. On the other hand, `Outlet_Type_Grocery Store` has a negative impact, indicating that grocery stores tend to generate lower sales compared to other outlet types. `Outlet_Type_Supermarket Type3` shows a positive contribution, suggesting better sales performance for this outlet type.

![Linear Regression Coefficients](linear_regression_coefficients.png)

### Random Forest Feature Importance
The Random Forest model identifies which features are most important for predicting sales. The top features include `Item_MRP`, `Outlet_Type_Grocery Store`, `Outlet_Type_Supermarket Type3`, `Item_Visibility`, and `Outlet_Identifier_OUT027`.

`Item_MRP` is the most important feature, meaning price plays a major role in determining sales. Store type is also highly influential, while product visibility indicates that better placement can improve sales performance.

![Random Forest Feature Importance](random_forest_feature_importance.png)

## Final Recommendations
Based on the analysis, businesses should focus on optimizing pricing strategies, improving product visibility, and prioritizing high-performing outlet types. These factors have the strongest impact on sales and can help increase overall performance.
