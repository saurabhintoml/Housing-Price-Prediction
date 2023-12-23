# Housing-Price-Prediction Model


This project is aimed at predicting housing prices based on various features such as construction year, total area, location, and more. We'll use machine learning techniques to build a predictive model for housing prices.

# Table of Contents
Dataset
Exploratory Data Analysis
Data Preprocessing
Machine Learning Model
Evaluation
Usage
Dataset
We use the "world_real_estate_data.csv" dataset, which contains information about real estate properties, including features like building construction year, total area, location, and more.

# Exploratory Data Analysis
We started the project by exploring the dataset to gain insights into its structure and contents. This included displaying the first few rows, checking for missing values, visualizing data distributions, and examining correlations between features.

# Data Preprocessing
To prepare the data for machine learning, we performed several preprocessing steps, including:

# Handling missing values by imputing them with appropriate strategies.
Encoding categorical variables using label encoding.
Converting area strings to numerical values.
Creating a new feature "Building Age."
Machine Learning Model
We used a Linear Regression model for predicting housing prices. The model was trained on the preprocessed data, and predictions were made on a test dataset.

# Evaluation
We evaluated the model's performance using the following metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
The model's performance metrics are as follows:

MAE: 267985.06
MSE: 493368413982.23
RMSE: 702401.89


