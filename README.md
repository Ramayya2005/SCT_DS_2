Titanic Survival Prediction

Overview

This project aims to predict the survival of Titanic passengers using various machine learning models. The dataset includes features such as age, sex, and ticket class, which are used to train and evaluate different classification algorithms. The goal is to analyze the dataset, preprocess the data, and apply several classification models to predict passenger survival.

Files

- task2.py: The main program that deals with the analysis of the data.
- train.csv: Training dataset with features and survival labels.
- test.csv: Testing dataset with features only (used for predictions).

Data Exploration and Preprocessing

1. Loading Data: Data is loaded from CSV files using pandas.

2. Data Inspection: The first few rows, dataset shape, and basic statistics of the data are inspected.

3. Missing Values and Duplicates: Check for and handle missing values and duplicate entries.

4. Exploratory Data Analysis (EDA):
   - Visualize the distribution of genders and survival status.
   - Analyze survival rates based on ticket class and age.
   - Plot histograms for age groups of survivors and non-survivors.
   - Visualize survival rates based on embarkation points using pie charts.

5. Data Cleaning:
   - Drop irrelevant columns (Ticket, Cabin, Name).
   - Handle missing values in Age and Embarked columns.
   - Encode categorical variables (Sex and Embarked).

Model Training and Evaluation

1. Model Training:
   - Split data into training and testing sets.
   - Train and evaluate the following models:
     - Logistic Regression
     - Support Vector Machines (SVM)
     - K-Nearest Neighbors (KNN)
     - Naive Bayes
     - Decision Tree Classifier

2. Model Evaluation:
   - Calculate accuracy scores for each model.
   - Generate confusion matrices and classification reports for performance assessment.

3. Results:
   - Compare model performance using accuracy scores.
   - Display confusion matrices and detailed classification reports for each model.
