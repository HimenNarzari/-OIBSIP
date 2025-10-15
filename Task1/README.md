# Iris Species Prediction

## Project Overview

This project focuses on predicting the species of Iris flowers using
supervised machine learning classification. The dataset used is the
classic **Iris dataset**, which includes measurements of sepal and petal
dimensions for three Iris species: *Setosa*, *Versicolor*, and
*Virginica*.

The objective of the project is to build a machine learning model that
can accurately classify an Iris flower into one of these species based
on its feature values.

## Dataset

The dataset contains the following features: - **Id** -- Unique
identifier for each sample
- **SepalLengthCm** -- Length of the sepal in centimeters
- **SepalWidthCm** -- Width of the sepal in centimeters
- **PetalLengthCm** -- Length of the petal in centimeters
- **PetalWidthCm** -- Width of the petal in centimeters
- **Species** -- The class label (Setosa, Versicolor, Virginica)

## Steps and Methodology

### 1. Data Loading

The dataset was loaded using **pandas** for initial inspection,
exploration, and validation of column types and structure.

### 2. Data Visualization

Exploratory Data Analysis (EDA) was conducted using **matplotlib** and
**seaborn** to visualize relationships among variables.
Plots such as pairplots and correlation heatmaps were used to understand
the separability between classes and identify feature importance.

### 3. Data Preprocessing

The data was checked for missing or inconsistent values. Features were
selected and encoded where necessary. 

### 4. Train-Test Split

The dataset was split into training and testing subsets to evaluate
model generalization. A random state was fixed for reproducibility.

### 5. Model Training

A **Logistic Regression** model was trained on the dataset to classify
the species of Iris flowers based on the four numerical features.

### 6. Model Evaluation

Model performance was evaluated using: - **Accuracy Score** -
**Cross-validation techniques** for consistency and reliability of the
results.

### 7. Results and Insights

The trained model achieved high accuracy in predicting Iris species,
confirming that the selected features effectively represent the class
differences among *Setosa*, *Versicolor*, and *Virginica*.

## Conclusion

This project demonstrates how a simple yet powerful classification
algorithm like Logistic Regression can achieve strong performance on a
well-structured dataset. It provides a foundation for comparing other
classification models or expanding into deeper analysis using ensemble
methods.
