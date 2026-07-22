# Oil Sales Prediction

## Project Overview

This project aims to predict oil sales using machine learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

## Objective

Develop a machine learning model to predict **Value Sales** based on product and sales information.

## Dataset

**Dataset:** Oil Sales Dataset (Synthetic)

### Features

- City
- Store Name
- Manufacturer
- Brand
- Product Class
- Size
- Price Bracket
- Year
- Month
- Volume Sales
- Average Price

**Target Variable**

- Value Sales

## Data Preprocessing

The following preprocessing steps were performed:

- Handle duplicated raws
- Handled missing values
- Drop useless columns
- Handle columns values

## Machine Learning Model

Model used:

- Linear Regression

## Evaluation Metrics

- Mean Absolute Error (MAE)
- R² Score

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```
Oil-Sales-Prediction/
│
├── README.md
├── Oil_Sales_Assignment.ipynb
└── oil_sales_assignment_dataset.csv
```

## Results

An R² score of 0.85 was obtained on both training and testing data, demonstrating a balanced fit. The consistency between train and test performance suggests the model generalizes well without overfitting or underfitting.
