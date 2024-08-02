# Problem Statement
Accurate weather prediction is essential for agriculture, disaster management, and daily life. This project aims to predict the minimum and maximum temperatures for the next day using historical weather data. The dataset, provided by the Korea Meteorological Administration, covers Seoul, South Korea from 2013 to 2017 and includes features such as present temperatures, humidity, wind speed, and more.

# Tools Used
Data Analysis: Python libraries including pandas, matplotlib, seaborn
Pre-processing: numpy, pandas, scipy.stats, sklearn (for data cleaning, feature engineering, and scaling)
Machine Learning: scikit-learn (Linear Regression, Lasso, Ridge, Decision Tree, Random Forest, XGBoost, SVR), xgboost for XGBoost model
Model Evaluation: Metrics from sklearn.metrics (R2 score, MSE, MAE, Cross-Validation)

# Findings
Overall Trends: Significant seasonal variations were observed, with the highest maximum temperature in August 2016 and the lowest minimum temperature in June 2014. The LDAPS model’s accuracy varied over the years.
Model Performance: XGBoost was the best for predicting minimum temperatures with 91% accuracy, while Random Forest excelled in predicting maximum temperatures with 98% accuracy.
Correlation Insights: Previous day temperatures strongly influence next day temperatures. Higher cloud cover and precipitation were associated with lower temperatures, while higher humidity linked to increased temperatures.
