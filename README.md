# Machine-Learning-For-User-Classification in Python

# Project Overview
This project aims to develop and evaluate machine learning models for predicting customer behavior, particularly focusing on determining if a customer will make a purchase based on various activity metrics. By leveraging data preprocessing, feature engineering, and modeling, the project showcases the complete machine learning workflow, from data cleaning to model selection.

# Project Objectives
Understand and explore customer behavior data, including feature distributions and potential relationships.
Preprocess the data, handle missing values, remove outliers, and encode features.
Reduce multicollinearity using Variance Inflation Factor (VIF).
Train and evaluate multiple models including Logistic Regression, K-Nearest Neighbors, Support Vector Machines, Decision Trees, and Random Forests.
Optimize data transformations for improved model accuracy and interpretability.

# Data Preprocessing Steps
Handling Missing Values: Missing values were filled using the median for numerical columns and the mode for categorical columns.
Outlier Removal: Outliers were removed based on predefined thresholds to ensure robust model training.
Feature Scaling and Encoding: Applied standardization to numerical columns and one-hot encoding to categorical columns to prepare the dataset for modeling.

# Models Used
Logistic Regression: A baseline model used for binary classification.
K-Nearest Neighbors (KNN): A distance-based classifier that considers the nearest neighbors for predictions.
Support Vector Machine (SVM): A classifier that finds a hyperplane that best separates classes.
Decision Tree: A non-parametric model that splits the data into decision rules.
Random Forest: An ensemble method that combines multiple decision trees for improved accuracy.

# Results and Evaluation
Each model was trained and evaluated using accuracy metrics and a detailed classification report. The performances of the models were compared to determine which best predicts customer behavior.

# Key Findings
Data preprocessing, including handling outliers and multicollinearity, significantly improved model performance.
The Random Forest model achieved the highest accuracy, showcasing the benefits of ensemble learning methods.
