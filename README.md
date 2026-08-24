# Car Price Prediction with Machine Learning

A Machine Learning project that predicts the selling price of used cars based on features such as present price, car age, driven kilometers, fuel type, transmission, selling type, and ownership.

The project demonstrates a complete Machine Learning workflow including data preprocessing, feature engineering, categorical encoding, model training, model evaluation, and visualization.

---

## Project Overview

The objective of this project is to build regression models capable of predicting car selling prices using historical car-related data.

Two regression algorithms were implemented and compared:

- Linear Regression
- Random Forest Regressor

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Objectives

- Load and understand the car price dataset
- Clean and preprocess the data
- Remove duplicate records
- Check and handle missing values
- Perform feature engineering
- Create a `Car_Age` feature
- Encode categorical variables
- Split the dataset into training and testing sets
- Train regression models
- Evaluate model performance
- Compare different regression algorithms
- Visualize actual vs predicted prices
- Analyze feature impact on car selling price

---

## Dataset

The dataset contains **301 records initially** and **9 original features**.

After removing duplicate records:

- Final records: **299**
- Original features: **9**
- Engineered feature: **Car_Age**
- Final model features: **9 input features**

### Original Features

| Feature | Description |
|---|---|
| `Car_Name` | Name of the car |
| `Year` | Manufacturing year |
| `Selling_Price` | Target selling price |
| `Present_Price` | Current/existing price |
| `Driven_kms` | Kilometers driven |
| `Fuel_Type` | Fuel category |
| `Selling_type` | Dealer or Individual |
| `Transmission` | Manual or Automatic |
| `Owner` | Number of previous owners |

---
## actual_vs_predicted_car_prices.png
Visualizations/actual_vs_predicted_car_prices.png



## Data Preprocessing

The following preprocessing steps were performed:

1. Dataset loaded using Pandas.
2. Dataset structure and data types were inspected.
3. Missing values were checked.
4. Duplicate records were identified.
5. Duplicate rows were removed.
6. Missing values were verified after cleaning.
7. A new `Car_Age` feature was created.
8. Categorical variables were converted into numerical features using one-hot encoding.

After cleaning:

```text
Dataset Shape: (299, 9)







