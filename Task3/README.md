# Car Price Prediction

## Project Overview

This project aims to predict the selling price of used cars based on
various car features using machine learning regression techniques. The
dataset contains details about different car attributes such as year,
fuel type, selling type, transmission, and more. The goal is to build a
model that accurately estimates car prices based on these features.

## Dataset

The dataset used in this project includes the following columns: -
**Car_Name** -- Name of the car model
- **Year** -- Year of manufacture
- **Selling_Price** -- Price at which the car is being sold\
- **Present_Price** -- Current ex-showroom price of the car\
- **Driven_kms** -- Total distance driven by the car in kilometers\
- **Fuel_Type** -- Type of fuel used (Petrol/Diesel/CNG)\
- **Selling_type** -- Indicates whether the car is being sold by a
dealer or individual
- **Transmission** -- Type of transmission (Manual/Automatic)\
- **Owner** -- Number of previous owners

## Steps and Methodology

### 1. Data Loading

The dataset was imported and inspected using **pandas** to understand
the structure, types of features, and missing values.

### 2. Data Cleaning

The dataset was already clean and did not require major modifications or
removal of records.

### 3. Data Preprocessing

Categorical features such as **Fuel_Type**, **Selling_type**, and
**Transmission** were encoded into numerical format to prepare the data
for model training. The features were then separated into input
variables (X) and target variable (y).

### 4. Feature Scaling

Feature scaling was performed using **StandardScaler** to normalize the
numerical features, ensuring consistent model performance.

### 5. Train-Test Split

The dataset was divided into training and testing sets using an 80:20
ratio to evaluate the model's predictive capability.

### 6. Model Training

Regression models were trained to predict car prices. The notebook
includes: - Model selection - Model fitting on training data -
Evaluation using performance metrics

### 7. Model Evaluation

Performance of the trained model was evaluated using: - **R² Score** -
**Mean Absolute Error (MAE)**

These metrics were used to assess the accuracy and reliability of the
model predictions.

## Results

The model successfully predicted car prices with a reasonable accuracy
score, demonstrating effective handling of both categorical and
numerical variables. The project highlights how data preprocessing and
feature engineering contribute to improved model performance.

## Conclusion

This project demonstrates the application of supervised machine learning
techniques for regression-based price prediction. It serves as a strong
foundation for further enhancements, such as hyperparameter tuning or
integration of ensemble models for improved results.
