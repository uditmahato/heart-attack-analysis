# HEART ATTACK ANALYSIS

## Overview

This project focuses on analyzing and predicting heart attacks. We aim to understand the factors and attributes that contribute to heart attacks and build predictive models using machine learning to assist in early detection.

## Packages

In this project, we make use of several Python libraries for data analysis and machine learning:

- `pandas`: Used for data manipulation.
- `numpy`: For numerical operations and array manipulations.
- `matplotlib` and `seaborn`: For data visualization.
- `plotly.express`: For interactive and high-quality visualizations.

## Understanding the Data

- We begin by loading the heart attack dataset from a CSV file using `pandas`.
- The dataset contains various columns such as age, sex, chest pain type, resting blood pressure, cholesterol level, fasting blood sugar, electrocardiogram results, thalium stress test results, and more.
- We have a target column named 'output', which indicates whether a person had a heart attack (1) or not (0).

## Data Visualization

We perform Exploratory Data Analysis (EDA) to gain insights and visualize the data. Here are some of the visualizations we create:

- Gender distribution
- Chest pain types
- Fasting blood sugar
- Electrocardiogram results
- Exercise-induced angina
- Thalium stress test results
- Age distribution
- Resting blood pressure
- Cholesterol levels
- And more

We also explore correlations between different features and the target variable using a correlation matrix and visualizations.

## Data Preprocessing

- We check for missing values in the dataset and find that it's clean; there are no missing values.
- Since there are no categorical features in the dataset, we don't need to perform categorical encoding.

## Data Splitting and Feature Scaling

- We split the dataset into a training set and a testing set using `train_test_split`.
- Feature scaling is applied to standardize the features, ensuring smooth convergence for machine learning algorithms.

## Machine Learning Algorithms

We use two machine learning algorithms to build predictive models:

1. **Random Forest (Decision Tree):**
   - We use the RandomForestRegressor from scikit-learn.
   - Achieves an accuracy of approximately 85%.
   - Provides a classification report and confusion matrix for evaluation.

2. **Support Vector Machine (SVM):**
   - We employ the Support Vector Classifier (SVC) from scikit-learn.
   - Achieves an accuracy of approximately 82%.
   - Includes a classification report and confusion matrix for evaluation.

## Conclusion

This project serves as a data analysis and machine learning exercise to understand factors related to heart attacks and predict them using data. The results of the predictive models can be further fine-tuned and integrated into a healthcare application for early detection of heart-related issues.

## Author

[uditmahato]

Feel free to customize the README with additional information or instructions specific to your project.
