Data Description

The dataset comprises the following features:

Daily Time Spent on Site: The average time (in minutes) a user spends on the website daily.
Age: The user's age in years.
Area Income: The average income within the user's geographical area.
Daily Internet Usage: The average daily internet usage time (in minutes) by the user.
Ad Topic Line: The headline text of the advertisement.
City: The user's city.
Male: A binary indicator (1 for male, 0 for female).
Country: The user's country.
Timestamp: The timestamp of the user's interaction with the ad (click or window close).
Clicked on Ad: A binary target variable indicating whether the user clicked on the ad (1) or not (0).
Project Objectives

Data Preprocessing:

Exploratory Data Analysis (EDA) to understand the data distribution and relationships between features.
Handling missing values and categorical variables (e.g., one-hot encoding, label encoding).
Feature scaling (if necessary) to ensure features are on similar scales and contribute equally to the model.
Model Training and Evaluation:

Split the data into training and testing sets for unbiased model evaluation.
Train a Logistic Regression model on the training set, fine-tuning hyperparameters for optimal performance.
Evaluate the model's performance on the testing set using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
Analysis and Interpretation:

Analyze the model's coefficients to understand the impact of each feature on click-through rates.
Identify the most influential features for ad click prediction.
Draw insights and recommendations based on the model's results.
Expected Benefits

Gain practical experience with Logistic Regression for binary classification.
Explore feature engineering techniques for categorical and numerical data.
Learn to evaluate and interpret Logistic Regression models.
Build a predictive model to understand user behavior and improve ad targeting strategies (potential future application).
Required Tools and Libraries

Python (version 3.x recommended)
NumPy
Pandas
Scikit-learn (specifically sklearn.linear_model.LogisticRegression, sklearn.model_selection, sklearn.metrics)
Matplotlib or Seaborn (for data visualization)

This project was completed as part of the Python for Data Science and Machine Learning Bootcamp
