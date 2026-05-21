# Telecom Customer Churn Prediction

## Overview
This project predicts whether a telecom customer will churn or not using machine learning techniques.

## Dataset
The dataset contains customer demographics, account details, services subscribed, and churn information.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow
1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. Data Preprocessing
5. Model Training
6. Model Evaluation

## Models Used
- Logistic Regression
- Decision Tree Classifier

## Hyperparameter Tuning
GridSearchCV was used to find the optimal hyperparameters for the Decision Tree Classifier, improving model performance and reducing overfitting.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- AUC Score

## Results
The tuned Decision Tree model was evaluated using multiple classification metrics. ROC Curve and AUC Score were used to measure the model's ability to distinguish between churn and non-churn customers.

## Key Insights
- Customers with higher monthly charges showed a greater tendency to churn.
- Contract type significantly influenced customer retention.
- Hyperparameter tuning improved model generalization performance.

## Conclusion
Machine learning techniques can effectively predict customer churn. Hyperparameter tuning and ROC-AUC analysis helped improve and validate model performance.

## Author
Devi
