# Insuranceproject
# Medical Insurance Cost Prediction
This project uses a dataset of medical insurance information to predict individual insurance charges based on demographic and lifestyle factors.

# Dataset
The dataset (insurance.csv) contains 1338 records with the following features:

. age: Age of the individual

. sex: Gender (male/female)

. bmi: Body Mass Index

. children: Number of children

. smoker: Smoking status (yes/no)

. region: Geographic region in the US

. charges: Annual medical insurance cost (target variable)

# Objective
The goal is to predict the charges using regression models based on the other features.

# Steps Performed
. Loaded and inspected the dataset

. Checked for missing values and basic data structure

. Explored data through visualizations

. Encoded categorical variables

. Trained and evaluated multiple regression models

  1. Linear Regression

  2. Lasso Regression

  3. Ridge Regression

. Evaluated models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score

# Conclusion
The models were able to learn meaningful patterns from the data. The final evaluation shows a good fit, with smoking status and BMI playing major roles in predicting insurance charges.

