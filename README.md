# Fastag Fraud Detection

![Fastag Fraud Detection](https://m.economictimes.com/thumb/msid-92496783,width-1600,height-900,resizemode-4,imgsize-62926/fastag-all-vehicles.jpg)

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

## Contributors

- Riyad Ahmadov
