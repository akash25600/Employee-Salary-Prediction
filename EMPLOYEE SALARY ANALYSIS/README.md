# Employee-Salary-Prediction

**Objective:**

Your task is to build a machine learning model that predicts the base salary of employees using the
provided dataset. You are expected to perform data exploration, preprocessing, feature engineering,
model building, and evaluation within a day.

**Data Exploration:**

Recognize the properties and structure of the dataset
Use fundamental statistical analysis to pinpoint the data's salient features.
univarient, bivarient & multivarient analysis of data set. 
i got meaningful insights from analysis 
histogramplot - how to distribute the each variable from the dataset. it will help to identify its normally distributed or not.
heatmap - how much strength have in the each variable compared to others, [division & deprtment has been highly correlated from the dataset]
boxplot - to identified the outlier [base_salary, overtime_pay, longvity_pay] these coloumns are contains outliers

**Data Preprocessing:**

Handle missing values - using fillna method to fill the missing values.
handle outliers - using capping method for changing to outliers value to corrected values.
Encode categorical variables - label encoding method will be used into catorical values to numerical values.
Split the data - Split the data into training and testing sets.

**Feature Engineering:**

Identify the features [Base_Salary] that might improve model performance.

**Model Building:**

Work with different machine learning algorithms (e.g., Linear Regression, Decision Trees, Random Forest, Gradient Boosting, etc.).
igot more accuracy in linear regression model compared with other models.

Linear Regression MSE: 0.009511914910418967, R²: 0.9999994362016347
Decision Tree MSE: 6350.427786748267, R²: 0.6235920065402036
Random Forest MSE: 2621.793155098221, R²: 0.8445988311470158
Gradient Boosting MSE: 1234.752982660588, R²: 0.9268126639292507
