OYO Rental Price Prediction in China
This project explores the use of machine learning techniques to predict rental prices for OYO properties in China. The aim is to optimize pricing strategies in the hospitality industry by identifying key factors influencing rental prices through data analysis and predictive modeling.

Project Overview
The dataset used in this project comes from Kaggle and contains information about OYO properties, including property features (such as amenities, bedrooms, bathrooms, and location) and rental price data. The project covers various stages including data preprocessing, feature selection, and the implementation of several machine learning models to predict rental prices.

Key Tasks:
Data Preprocessing: Cleaned and transformed data to handle missing values, converted categorical variables into numerical formats, and applied one-hot encoding to prepare the data for machine learning models.


Feature Selection: Used correlation analysis and RandomForestRegressor to identify key features influencing rental prices.

Model Implementation: Tested multiple machine learning models (Linear Regression, Random Forest, Gradient Boosting, and SVR) to predict rental prices, with Random Forest being the most accurate.

Model Evaluation: Compared models using metrics such as R², MAE, and MSE, and identified Random Forest as the best model for regression tasks based on its superior predictive performance.

Key Findings:
Best Model: Random Forest provided the most accurate predictions for rental prices with the highest R² value (0.5290) and lowest MAE (125.57).

Important Features: Bathrooms, bedrooms, and location (latitude) were identified as the most important factors influencing rental prices.

Clustering: K-Means clustering was found to be ineffective due to a low silhouette score, indicating it was not suitable for this dataset.

Conclusion:
This project demonstrates the practical application of machine learning in the hospitality sector to optimize pricing strategies for OYO properties in China. The Random Forest model provides the most reliable predictions, helping businesses better understand the factors driving rental prices.

Files in this Repository:
Data Preprocessing Code: Scripts for cleaning and preparing the dataset.

Modeling Code: Code for training and testing machine learning models.

Visualizations: Various plots that illustrate the relationship between features and rental prices.
