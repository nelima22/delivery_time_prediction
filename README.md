# Predicting Food Delivery Duration

![Alt Text](https://github.com/nelima22/delivery_time_prediction/blob/main/images%20(12).jpeg)

## Project Overview
This project aims to predict the duration of food delivery using a food delivery dataset. The process involves data exploration, visualization, feature engineering, preprocessing, and model selection using three different models to identify the best performing one.


## Introduction
The objective of this project is to build a predictive model that can accurately estimate the delivery time of food orders. This can help food delivery services optimize their logistics and improve customer satisfaction.

## Data Exploration
The initial step involves understanding the dataset by exploring its structure and summary statistics. We will look at the following aspects:
- Inspecting the first few rows of the dataset
- Checking for null values
- Understanding the data types of each feature
- Summarizing the statistics of numerical and non-numerical features

## Feature Engineering
Feature engineering involves creating new features or transforming existing ones to improve the performance of the model. In this project, we will:
- Create new time-based features such as hour of the day, day of the week, etc.
- Encode categorical features 
- Handle missing values appropriately
- Esnure everything has the correct data type

## Preprocessing
Preprocessing steps ensure that the data is in the right format for modeling. This includes:
- Scaling numerical features
- Splitting the dataset into training and testing sets

## Modeling
We will experiment with three different models and use Grid Search Cross-Validation (Grid Search CV) to fine-tune the hyperparameters. The models considered are:
1. Linear Regression
2. Random Forest Regressor
3. Decision Tree Regessor
Grid Search CV helps in finding the best combination of hyperparameters for each model.

## Results
After training the models, we will evaluate their performance using appropriate metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The model with the best performance will be selected as the final model.

## Conclusion
The project demonstrates the process of building a predictive model for food delivery duration. Key takeaways include the importance of data preprocessing, feature engineering, and model selection.

We tested three models;Linear Rrgressor, Decision Tree Regressor and Random Forest Regressor. It was determined that the Ramdom Forest regressor performed best. The model was evaluated using several metrics to assess its performance, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

The model's R2 score of 0.81 indicates a high level of explanatory power, suggesting that the model captures the majority of the variability in the data. The low MAE and RMSE values further support that the model makes predictions with relatively small errors. Together, these metrics indicate that the model performs well in terms of both accuracy and reliability.

## References
1. [Food Felivery Dataset from Kaggle](https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset/data?select=test.csv)
 
