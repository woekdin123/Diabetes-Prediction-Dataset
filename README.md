# Diabetes Prediction Dataset
## Overview
This dataset contains 100,000 records of patient health data related to diabetes prediction. It includes demographic details, medical history, and laboratory test results. The dataset can be used for statistical analysis and machine learning applications for diabetes risk prediction.
## 1. Objective
To predict diabetes based on patient data using Machine Learning.
To preprocess data, visualize patterns, and evaluate classification performance.
To apply Support Vector Machine (SVM) for binary classification.
## 2. Modules and Software Used
The script utilizes several Python libraries:

Module	Purpose
numpy & pandas	Handling numerical operations and managing datasets.
matplotlib.pyplot & seaborn	Data visualization for EDA.
sklearn.model_selection	Splitting dataset into training and test sets.
sklearn.preprocessing	Standardization (StandardScaler) and encoding (LabelEncoder).
sklearn.svm	Implements Support Vector Machine (SVM) for classification.
sklearn.metrics	Evaluating model performance using accuracy.
## 3. Approach Used
The Supervised Learning Approach is used, specifically:

Classification Problem: Since diabetes is binary (0 or 1).
Machine Learning Pipeline:
Data Cleaning & Preprocessing
Feature Engineering
Exploratory Data Analysis (EDA)
Data Splitting (Train-Test)
Feature Scaling (Standardization)
Model Training (SVM)
Model Evaluation (Accuracy Score)
## 4. Expected Output
Data Visualizations (Histograms, Correlation Heatmap, Boxplots).
Training Accuracy (How well the model learns the patterns).
Testing Accuracy (How well the model generalizes to unseen data).
