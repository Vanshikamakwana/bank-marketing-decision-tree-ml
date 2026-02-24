# Bank Marketing Prediction using Decision Tree Classifier

## Project Overview

This project analyzes a bank marketing dataset to predict whether a customer will subscribe to a term deposit. A Decision Tree classification model was built and optimized using hyperparameter tuning to improve prediction performance.

## Objective

To identify potential customers who are likely to subscribe to a term deposit, helping banks improve marketing campaign efficiency and reduce operational costs.

## Tools & Libraries Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Machine Learning Techniques Applied

* Label Encoding (for categorical variables)
* MinMax Scaling (feature normalization)
* Train-Test Split (80-20 split)
* Decision Tree Classifier
* Hyperparameter Tuning using GridSearchCV
* Model Evaluation using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report

## Project Workflow

1. Data Loading and Inspection
2. Handling Categorical Variables using LabelEncoder
3. Feature Scaling using MinMaxScaler
4. Splitting dataset into training and testing sets
5. Building Decision Tree model with entropy criterion
6. Hyperparameter tuning (criterion, splitter, max_depth)
7. Model evaluation and visualization using confusion matrix heatmap

## Key Insights

* Decision Tree model successfully classified customer subscription behavior.
* Hyperparameter tuning improved model performance.
* Model evaluation metrics provided clear understanding of prediction quality.

## Results

The optimized Decision Tree model achieved strong accuracy on both training and testing datasets, demonstrating effective classification performance.

## Business Impact

* Helps bank identify high-probability customers
* Improves marketing ROI
* Supports data-driven targeting strategy
