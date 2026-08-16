# synent-task8-house-price-prediction-MUTHUESWARAPANDIAN


🏠 House Price Prediction using Machine Learning

📌 Project Overview

This project focuses on building a Machine Learning model to predict house prices using the House Price Prediction Dataset.

🎯 Objective

The main objective of this project is to build a prediction model for house prices.

📂 Dataset

Dataset: House Price Prediction Dataset

Target Variable: Price

🔧 Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

🔄 Project Workflow

1. Data Preprocessing

- Checked missing values
- Checked duplicate records
- Removed unnecessary Id column
- Removed duplicate rows
- Filled missing numerical values using median
- Filled missing categorical values using mode
- Converted categorical variables using One-Hot Encoding
- Handled outliers using the IQR method

2. Feature Selection

- Separated input features (X)
- Selected Price as the target variable (y)
- Applied StandardScaler for feature scaling

3. Train-Test Split

- 80% Training Data
- 20% Testing Data
- random_state = 42

🤖 Machine Learning Models

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Tuned Random Forest Regressor

📊 Model Evaluation

The models were evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

📈 Output

A working Machine Learning model for house price prediction with model evaluation and comparison.

📌 Internship Task

Task 8 – Machine Learning Model

Completed as part of the Data Science Internship Program at Synent Technologies.
