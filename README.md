![image](https://github.com/RiyadAhmadov/Mentorness/assets/116457780/a4459ebd-2729-4bac-a8e3-38f35bae493f)# Fastag Fraud Detection

![Fastag Fraud Detection](https://www.airswift.com/hubfs/remote%20data%20scientist%20working.jpg)

# Project 1: Fastag fraud detection
## Dataset Description

The dataset contains the following columns:

1. **Transaction_ID**: Unique identifier for each transaction.
2. **Timestamp**: Date and time of the transaction.
3. **Vehicle_Type**: Type of vehicle involved in the transaction.
4. **FastagID**: Unique identifier for Fastag.
5. **TollBoothID**: Identifier for the toll booth.
6. **Lane_Type**: Type of lane used for the transaction.
7. **Vehicle_Dimensions**: Dimensions of the vehicle.
8. **Transaction_Amount**: Amount associated with the transaction.
9. **Amount_paid**: Amount paid for the transaction.
10. **Geographical_Location**: Location details of the transaction.
11. **Vehicle_Speed**: Speed of the vehicle during the transaction.
12. **Vehicle_Plate_Number**: License plate number of the vehicle.
13. **Fraud_indicator**: Binary indicator of fraudulent activity (target variable).

## Project Overview

This project aims to develop a fraud detection system for toll transactions using machine learning techniques. The dataset provided contains information about various toll transactions, including details such as transaction ID, timestamp, vehicle type, transaction amount, and a binary indicator of fraudulent activity.

## Approach

1. **Data Preprocessing**: The dataset will be preprocessed to handle missing values, encode categorical variables, and scale numerical features if necessary.
2. **Model Training**: Several machine learning models will be trained on the preprocessed data, including decision trees, random forests, and gradient boosting classifiers.
3. **Model Evaluation**: The performance of each model will be evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score.
4. **Model Selection**: The best-performing model will be selected based on evaluation metrics and deployed for fraud detection.

## Usage

To use this fraud detection system:

1. **Data Preparation**: Ensure the input data is in the same format as the provided dataset, with the required columns.
2. **Model Deployment**: Deploy the trained machine learning model to predict fraudulent transactions based on the input data.
3. **Prediction**: Use the deployed model to predict whether a transaction is fraudulent or not based on its features.

## Requirements

To run the code, the following dependencies are required:

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- gradio

# Project 2: Salary Prediction Model

![Salary Prediction Model](https://repository-images.githubusercontent.com/293898841/c91e7100-5e42-11eb-9820-2f68d80ed516)

This project aims to build a machine learning model that predicts the salary of data professionals based on various features such as personal information, job details, and performance metrics. The model uses a Random Forest Regressor, and the application is deployed using Gradio for easy user interaction.

## Dataset Overview

The dataset contains the following columns:

- `FIRST NAME`: First name of the employee
- `LAST NAME`: Last name of the employee
- `SEX`: Gender of the employee
- `DOJ`: Date of joining the company
- `CURRENT DATE`: The current date of the data
- `DESIGNATION`: Job role/designation of the employee
- `AGE`: Age of the employee
- `SALARY`: Target variable, the salary of the employee
- `UNIT`: Business unit or department
- `LEAVES USED`: Number of leaves used by the employee
- `LEAVES REMAINING`: Number of leaves remaining for the employee
- `RATINGS`: Performance ratings of the employee
- `PAST EXP`: Past work experience of the employee (in years)

## Project Pipeline

1. **Exploratory Data Analysis (EDA)**: Understand the dataset through visualization and summary statistics.
2. **Feature Engineering**: Create new features or transform existing ones to improve model performance.
3. **Data Preprocessing**: Handle missing values, encode categorical variables, and scale/normalize features as needed.
4. **Model Development**: Train various regression models to predict salaries. Experiment with different algorithms such as linear regression, decision trees, random forests, and gradient boosting.
5. **Model Evaluation**: Assess model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) score.
6. **ML Pipelines and Model Deployment**: Create ML pipelines to streamline the process from data preprocessing to model training. Deploy the model using Gradio.
7. **Recommendations**: Provide actionable insights based on the model's predictions and findings.

## Preprocessing and Feature Engineering

1. **Date Features**: Extract month and year from the date of joining (`DOJ`).
2. **Grouping**: Group `AGE` and `PAST EXP` into categories.
3. **Leave Calculations**: Calculate the percentage of leaves used.
4. **Tenure Calculation**: Calculate the tenure of employees from the date of joining to the current date.
5. **Encoding**: Encode categorical features using one-hot encoding.

## Model Training

The project uses a Random Forest Regressor as the primary model. The trained model is saved as a pickle file (`best_rf_regressor.pkl`) for deployment.

## Deployment with Gradio

The application uses Gradio to provide a user-friendly interface for salary prediction.

## Contributors

- Riyad Ahmadov
