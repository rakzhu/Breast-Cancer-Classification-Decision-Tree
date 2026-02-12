# Breast Cancer Classification using Decision Tree

# Project Overview

This project implements a supervised machine learning classification model to predict whether a breast tumor is:
Malignant (1)
Benign (0)
The model is built using a Decision Tree Classifier from Scikit-Learn.
The objective is to understand the full ML pipeline including:
Data loading
Data cleaning
Feature selection
Train-test split
Model training
Model evaluation
Hyperparameter tuning

# Dataset

The dataset contains diagnostic measurements of breast cancer tumors.
Each row represents a tumor sample with multiple numerical features extracted from cell nuclei images.
Target variable:
diagnosis
M = Malignant
B = Benign

# Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn

# Project Workflow
1. Data Preprocessing
Loaded dataset using Pandas
Checked for missing values
Removed unnecessary id column
Converted categorical diagnosis to numerical format

2. Exploratory Data Analysis (EDA)

Visualized class distribution using Seaborn
Checked dataset dimensions

3. Model Building

Split data into training and testing sets
Trained a Decision Tree classifier
Generated predictions

4. Model Evaluation

Confusion Matrix
Accuracy Score

5. Hyperparameter Tuning

Tested multiple tree depths (1–20)
Used 10-fold Cross Validation
Compared training accuracy vs validation accuracy

# Results

Model accuracy evaluated using confusion matrix and accuracy score.
Depth tuning performed to prevent overfitting.
Cross-validation used to improve model reliability.
