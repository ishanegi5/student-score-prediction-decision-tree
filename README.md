📘 Student Score Prediction — Decision Tree Regressor
📌 Overview

This project demonstrates the use of Decision Tree Regressor with OneHotEncoding and GridSearchCV to predict student scores based on demographic and test-related features.
The project highlights data preprocessing, model building, hyperparameter tuning, and regression evaluation.

📂 Dataset

Source: Student Performance dataset (CSV format).

Features include categorical attributes (gender, race/ethnicity, parental education, lunch type, test preparation) and numeric attributes (math, reading, writing scores).

The target variable was chosen as [math_score].

🛠️ Steps Performed

Data Preprocessing

Handled categorical variables using OneHotEncoding.

Split dataset into train & test sets.

Model Building

Implemented a Decision Tree Regressor.

Performed GridSearchCV to find best hyperparameters.

Evaluation Metrics

RMSE = 11.23

MAE = 9.03

R² Score = 0.26

🔑 Best Parameters (GridSearchCV)
{'max_depth': 7, 'min_samples_leaf': 32, 'min_samples_split': 2}

📊 Results

The model shows moderate performance with R² ≈ 0.26, suggesting Decision Trees alone may not fully capture complex relationships in the dataset.
This highlights the importance of trying other regression models (Linear Regression, RandomForest, GradientBoosting, etc.) for better predictive performance.

🚀 Tech Stack

Python

Pandas, NumPy

Scikit-learn (DecisionTreeRegressor, GridSearchCV, metrics)

Matplotlib / Seaborn (visualization)

📌 Learning Outcome

Understanding regression with Decision Trees.

Handling categorical variables via OneHotEncoding.

Applying hyperparameter tuning using GridSearchCV.

Evaluating models using RMSE, MAE, R² score.
