# Employee Churn Classification

## Overview
This project aims to predict employee churn using machine learning techniques. The provided code includes data preprocessing, model training, and evaluation steps.

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - scikit-learn

## Usage
1. Ensure Python and required libraries are installed.
2. Clone the repository.
3. Place the employee dataset (`employee.csv`) in the appropriate directory.
4. Run the provided code.

## Code Breakdown
- **Data Loading:** The code loads the employee dataset using pandas.
- **Data Preprocessing:** 
  - Removes duplicates.
  - Handles missing values.
  - Splits the data into features (X) and target variable (y).
  - Splits the dataset into training and testing sets.
  - Preprocesses categorical features using one-hot encoding and ordinal encoding.
- **Model Training:** Trains a logistic regression classifier.
- **Model Evaluation:** 
  - Predicts employee churn.
  - Evaluates model accuracy.

## Results
The accuracy of the trained model on the test set is calculated and displayed.
