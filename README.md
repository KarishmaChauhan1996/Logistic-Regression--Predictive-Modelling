# Logistic-Regression--Predictive-Modelling

This repository contains a logistic regression model implemented for binary (or multi-class) classification. Logistic regression is a supervised machine learning algorithm used to predict the probability of a categorical dependent variable. This README will guide you through the project setup, data preprocessing, model building, evaluation, and insights.

**Table of Contents**

* Project Overview
* Dataset
* Dependencies
* Data Preprocessing
* Model Building
* Model Evaluation
* Insights and Interpretation

**Project Overview**

Logistic regression is a statistical method used for binary classification. This project applies logistic regression to predict class labels (such as "yes/no", "success/failure", or "spam/not spam") based on input features. The project demonstrates how to preprocess data, build a logistic regression model, evaluate its performance, and interpret the results.

**Dataset**

The dataset used in this project have the following characteristics:

* age: age
* workclass: workclass
* education: highest education
* marrital status: marital status
* occupation: occupation
* sex: sex
* capital gain: income from investment sources other than salary/wages
* capital loss: income from investment sources other than salary/wages
* working hours: nummber of working hours per week
* salary: salary


**Dependencies**

Make sure you have the following libraries installed:

Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn

**Data Preprocessing**

Data preprocessing is essential to improve the model's performance and accuracy. Steps include:

* Handling Missing Values: Filling or dropping missing values to ensure clean data.
* Handling duplicates.
* Handling special charatcers.
* Trating outliers.
* Converting all objects to categorical codes
* Encoding categorical variables.

  **Exploratory Data Analysis**
  
* Checking correlation between variables using heatmap, pairplot.


**Model Building**

* Train-test solit.
* Import Logistic Regression Model: The logistic regression model from scikit-learn is used in this project

  **Predicting on Training and Test dataset**
             -Getting the Predicted Classes and Probs

**Model Evaluation**

Model performance is evaluated using various metrics:

* AUC and ROC for the training data and test data.
* Confusion Matrix for the training data and test data:  A table showing true positives, false positives, true negatives, and false negatives

**Applying GridSearchCV for Logistic Regression**

**Insights and Interpretation**

* The logistic regression model provides insights into the importance of features in predicting the target variable. Interpreting the coefficients of logistic regression helps understand the direction and magnitude of relationships between features and the target variable.
* Overall accuracy of the model – 82 % of total predictions are correct.
* Accuracy, AUC, Precision and Recall for test data is almost inline with training data. This proves no overfitting or underfitting has happened, and overall the model is a good model for classification


