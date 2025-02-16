Traffic Prediction Using Machine Learning
This project aims to predict traffic situations using machine learning models based on vehicle counts and other traffic-related features. Two models, k-Nearest Neighbors (kNN) and Random Forest, are implemented to predict traffic conditions, evaluated using metrics such as accuracy, precision, and recall.

Project Overview
The dataset contains features such as:

CarCount: Number of cars.
BikeCount: Number of bikes.
BusCount: Number of buses.
TruckCount: Number of trucks.
Total: Total count of vehicles.
The target variable is Traffic Situation, categorized into four levels: low, normal, high, and heavy.

Key Steps
Data Preprocessing: Data cleaning, filling missing values, converting categorical variables, and normalizing vehicle count data.
Feature Engineering: Transforming 'Time' into minutes and applying label encoding to categorical columns.
Modeling: Training k-Nearest Neighbors (kNN) and Random Forest classifiers.
Evaluation: Using confusion matrices and calculating precision, recall, and accuracy to compare model performance.

Results
Classifier	                  Precision	Recall	Accuracy
k-Nearest Neighbors          	0.85	     0.84	    0.83
Random Forest	                0.88	     0.87	    0.86

Future Work
Include more advanced models like XGBoost or Neural Networks.
Improve feature engineering with additional data such as weather or geographic information.
Explore time-series forecasting models for future traffic predictions.
