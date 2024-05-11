# Sales Forecasting Project 

## Overview
This project focuses on sales forecasting using historical data from a retail company. The goal is to analyze the dataset, perform exploratory data analysis (EDA), handle outliers and poor data quality, and develop forecasting models to predict sales for June 2021.

## Data Set
The dataset contains information about products, manufacturers, area codes, sourcing channels, product sizes, product types, months of sourcing, and sourcing costs. It spans from June 2020 to May 2021 for the training set, and June 2021 for the test set.
Total Rows: 550,176
Total Columns: 8
ProductType
Manufacturer
Area Code
Sourcing Channel
Product Size
Product Type
Month of Sourcing
Sourcing Cost(Target)

## Exploratory Data Analysis (EDA)
The EDA process involves:
- Checking for missing values and handling them appropriately.
- Visualizing distributions, correlations, and trends in the data using Python libraries such as pandas, numpy, matplotlib, and seaborn.
- Identifying outliers and applying strategies like winsorization and data transformations to handle them.

## Handling Outliers and Poor Data Quality
The analysis employed robust outlier detection methods such as Z-score and IQR, visualized outliers through boxplots, and managed them through trimming, capping, and binning, ensuring data integrity and enhancing analysis outcomes for informed decision-making.

## Forecasting Approaches

1. Random Forest Regressor
2. Gradient Boosting Regressor
3. Extra Trees Regressor
4. Support Vector Regressor (SVR)
5. Linear Regression
6. Ridge Regression
7. Lasso Regression
8. ElasticNet Regression
9. K-Nearest Neighbors
10. Decision Tree Regressor
11. XGBoost Regressor
12. LightGBM Regressor
13. CatBoost Regressor
14. LSTM Model
15. Sequential Deep Learning Model

## The best performing model appears to be the XGBoost Regressor:

Mean Squared Error (MSE): 970.81
Mean Absolute Error (MAE): 15.93
Root Mean Squared Error (RMSE): 31.15
R-squared (R2) Score: 0.64

## Conclusion
By leveraging Python and its libraries for data analysis, EDA, outlier handling, and forecasting, this project aims to provide valuable insights and accurate predictions to support business decision-making in the retail industry.
XGBoost is a powerful ensemble learning technique that effectively handles non-linearity, controls overfitting through regularization, and provides feature importance for better model interpretability. Its ability to handle missing values and scalability make it an efficient choice for robust predictive modeling on large datasets.
