# Tasks-for-Data-Science-Interns-task-4-

# **Boston Housing Price Prediction**

This project implements **Linear Regression**, **Random Forest**, and **XGBoost** models from scratch (without using `sklearn.linear_model`, `RandomForestRegressor`, or `XGBoost`) to predict house prices using the Boston Housing dataset. The models are evaluated using **RMSE (Root Mean Squared Error)** and **R² Score**.

**Explaining the project steps**

1. Load Boston Housing dataset and normalize features.

2. Implement Linear Regression from scratch using gradient descent.

3. Build Decision Trees from scratch for Random Forest and XGBoost.

3. Combine multiple trees to create:

4. Random Forest (bagging of trees).

5. XGBoost (boosting with residual fitting).

6. Train all models on training data.

7. Evaluation Metrics: We evaluate each model on two key metrics:

->RMSE (Root Mean Squared Error) – Measures prediction error magnitude.

->R² Score (Coefficient of Determination) – Shows how well the predictions explain the variability in target.
      
8. Visualize feature importance from models.

** Observations / Results**

1. Linear Regression is simple and fast, but less accurate.

2. Random Forest improves accuracy by combining trees.

3. XGBoost gives the best performance, because it focuses on learning from previous mistakes.



**How to Run the Code**
1. Upload the boston.csv file in your environment.

Run each script one-by-one:

> linear_regression.py

> random_forest.py

> xgboost.py

Check printed RMSE and R² for performance comparison.
