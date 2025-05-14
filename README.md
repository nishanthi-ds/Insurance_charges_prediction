This project aims to develop a machine learning model to predict insurance charges based on individual characteristics. The model is built using a Random Forest algorithm, which is effective for regression tasks. The project includes the following steps:

## 1- Data Collection: 
The dataset includes insurance charge data with the following columns: age, sex, BMI, number of children, smoking status, and charges.

## 2- Data Preprocessing:
Categorical features such as sex and smoking status are transformed using one-hot encoding. The dataset is then split into training and testing sets to evaluate the model's performance.

## 3- Model Building:
A Random Forest Regressor is used as the predictive model. It works by constructing multiple decision trees and averaging their outputs for robust regression.

## 4- Model Training: 
The model is fine-tuned using Grid Search to find the optimal combination of hyperparameters such as the number of trees, maximum depth, and minimum samples per leaf.

## 5- Model Evaluation: 
The model's performance is assessed using the R² score, which measures how well the predictions approximate the actual values.
