# Titanic Survival Prediction Project

**Introduction:**

The sinking of the RMS Titanic in 1912 remains one of the most infamous maritime disasters in history. This project aims to utilize machine learning techniques to predict survival outcomes of passengers based on various characteristics such as age, gender, class, and embarkation details.

**Problem Statement:**

The objective of this project is to develop machine learning model that predicts the survival of Titanic passengers based on their demographic and socio-economic features. Using the Titanic dataset, which includes information such as passenger class, age, sex, and the number of siblings or spouses aboard, the model will be trained to identify patterns associated with survival. 

**Dataset:**

We have a separate train and test set, in which test set is without the Target Variable and we will be using it for Model Testing

We will be having the following columns:

PassengerId - A unique identifier for each passenger.

Survived - Survival indicator (0 = No, 1 = Yes) [Target Variable].

Pclass - Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).

Name - Name of the passenger.

Sex - Sex of the passenger.

Age - Age of the passenger.

SibSp - Number of siblings/spouses aboard the Titanic.

Parch - Number of parents/children aboard the Titanic.

Ticket - Ticket number.

Fare - Passenger fare.

Cabin - Cabin number.

Embarked - Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

**Project Description:**

• Performed in-depth exploration of the titanic dataset, identifying key patterns and relationships to understand factors influencing person survival.

• Performed Data Pre-processing and Feature Engineering in order to prepare data for modelling.

• Developed Machine Learning models such as Logistic Regression, Decision Tree, LightGBM, XGBoost, Extra Tree Classifier to predict Titanic Survival.

• Performed Cross Validation to improve the model performance

• Achieved an cross-validation score of 82% using LightGBM Model

**Observation:**

LightGBM Model performs better in this project when compared to other models.

**Skills:** Exploratory Data Analysis · Machine Learning · Logistic Regression · Decision Trees · LightGBM · XGBoost · Extra Tree Classifier · Data Pre-Processing · Feature Engineering · Cross Validation


