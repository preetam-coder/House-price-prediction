# House-price-prediction

🎯 Objective

The goal of this project is to implement and understand simple and multiple linear regression using Python and popular data-science libraries. The workflow includes data preprocessing, training a regression model, evaluating its performance, and visualizing results.

🛠 Tools & Technologies Used

Python

Pandas – data loading & preprocessing

NumPy – numerical operations

Scikit-learn – Linear Regression, model training, evaluation

Matplotlib / Seaborn – data visualization

📂 Project Workflow
1. Import & Preprocess Dataset

Load the dataset using Pandas

Handle missing values (if any)

Select features & target variables

Perform scaling/encoding if required

2. Split Dataset

Use train_test_split from sklearn

Training set & testing set separation

3. Train Linear Regression Model

Use sklearn.linear_model.LinearRegression()

Fit the model on training data

Extract coefficients & intercept

4. Model Evaluation

Metrics used:

MAE – Mean Absolute Error

MSE – Mean Squared Error

RMSE – Root Mean Squared Error

R² Score – Coefficient of Determination

5. Visualization

Plot regression line for simple regression

Scatter plot of actual vs. predicted values

Interpret slope, intercept & feature significance

📊 Results Summary

Regression model trained successfully

Error metrics used to evaluate performance

Visualization helps understand model fit and insights

Coefficients interpret how each independent variable impacts the target variable
