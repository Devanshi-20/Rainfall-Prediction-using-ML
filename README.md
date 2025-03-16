Kaggle Playground Series - 2025: Rainfall Prediction 🌧️
📌 Overview
Welcome to the 2025 Kaggle Playground Series! 🎉
This competition is part of a series designed to help data enthusiasts practice their machine learning skills on interesting and approachable datasets.

In this challenge, our goal is to predict daily rainfall for an entire year based on historical weather data.

📊 Dataset Description
The dataset contains various meteorological features, such as:

Pressure
Temperature (max, min, average)
Dew Point
Humidity
Cloud Coverage
Sunshine Duration
Wind Direction & Speed
Each row represents a single day, and the target variable is whether or not it rained on that day (rainfall as a binary classification problem).

🎯 Objective
Develop a machine learning model to predict the probability of rainfall on a given day. The model should output a probability score rather than a binary classification.

📌 Evaluation Metric
Submissions are evaluated based on the Area Under the ROC Curve (AUC-ROC).
A higher ROC-AUC score indicates a better-performing model.

💻 Approach
We implemented and compared the following models:
✅ Logistic Regression
✅ Random Forest Classifier
✅ XGBoost Classifier
✅ Deep Learning (Neural Networks - Optional Extension)

Steps followed:

Exploratory Data Analysis (EDA)
Data Preprocessing (handling missing values, feature scaling)
Feature Engineering
Model Training & Hyperparameter Tuning
Evaluation & Model Selection
