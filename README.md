# Sales Prediction Using Python

A machine learning project focused on predicting sales performance based on advertising spend across different channels.

## Overview

This project analyzes how marketing expenditure across TV, radio, and newspaper advertising affects sales. Using various regression models, it aims to provide accurate sales forecasts that can help optimize advertising budget allocation.

## Problem Statement 

Modern businesses need accurate sales forecasts to:
- Measure advertising effectiveness
- Target the right audience segments
- Select optimal advertising channels
- Make data-driven budget decisions

## Data

The dataset contains information about:
- TV advertising spend
- Radio advertising spend  
- Newspaper advertising spend
- Sales figures

## Models Implemented

The following regression models were tested and evaluated:

- Linear Regression
- Lasso Regression 
- Ridge Regression
- Decision Tree
- Gradient Boosting Regressor

## Key Results

- TV advertising showed the strongest correlation with sales
- Gradient Boosting Regressor achieved the best performance:
  - 99% accuracy on training data
  - 98% accuracy on test data
- Models were evaluated using R² scores, MSE, RMSE and MAE metrics

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- XGBoost

## Usage

1. Install required packages:
```bash
pip install numpy pandas scikit-learn seaborn matplotlib xgboost