# House Prices Prediction – Random Forest Regression

## Overview

This project implements a Random Forest Regression model to predict house prices using the Kaggle "House Prices - Advanced Regression Techniques" competition dataset. The notebook includes comprehensive data preprocessing, feature engineering, model training, and evaluation.

## Features

- **Data Preprocessing**: Handles missing values for both numeric and categorical features
- **Feature Encoding**: Uses Label Encoding for categorical variables
- **Target Transformation**: Applies log transformation to the target variable (SalePrice) to reduce skewness
- **Model Training**: Implements Random Forest Regression with scikit-learn
- **Evaluation Metrics**: Calculates RMSE (Root Mean Squared Error) and R² score
- **Feature Importance**: Visualizes the top 10 most important features
- **Submission Ready**: Generates a properly formatted submission file for Kaggle

## Requirements

- Python 3
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies with:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Dataset
The model uses the following datasets from the Kaggle competition:

- **train.csv**: Training data with features and target (SalePrice)
- **test.csv**: Test data for making predictions

## Usage
1. Ensure the dataset files (train.csv and test.csv) are in the working directory
2. Run the notebook cells sequentially
3. The final submission will be saved as submission.csv

## Model Performance
The model evaluation includes:
- RMSE (Root Mean Squared Error)
- R² (Coefficient of Determination)
