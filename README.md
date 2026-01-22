Heart Disease Prediction Using Logistic Regression
Overview

This project demonstrates the basic workflow of building and evaluating a machine learning classification model using the Heart Disease Dataset.
The goal is to help interns understand model training, testing, and evaluation metrics using Python and Scikit-learn.

Dataset

Name: Heart Disease Dataset

Features used:

Age

Sex

Chest pain type

BP

Cholesterol

FBS over 120

EKG results

Max HR

Exercise angina

ST depression

Slope of ST

Number of vessels fluro

Thallium

Target column:

Heart Disease

Presence → 1

Absence → 0

Tools & Technologies

Python

Google Colab

Scikit-learn

Pandas

Steps Performed
1. Data Loading

The dataset is loaded using Pandas and basic inspection is done.

2. Data Preparation

Feature columns are separated from the target column.

Target labels are converted from categorical values (Presence/Absence) to numerical values (1/0).

3. Train–Test Split

The dataset is split into:

Training set (80%) – used to train the model

Testing set (20%) – used to evaluate model performance

This helps measure how well the model performs on unseen data.

4. Model Training

A Logistic Regression model is trained using the training dataset.

5. Prediction

The trained model is used to predict heart disease on the test dataset.

6. Model Evaluation

The model is evaluated using:

Accuracy

Precision

Recall

Confusion Matrix

Special handling is added to avoid errors when working with small datasets.

Evaluation Metrics Explained

Accuracy: Overall correctness of predictions

Precision: How many predicted positive cases are actually positive

Recall: How many actual positive cases were correctly identified

Confusion Matrix: Shows true positives, true negatives, false positives, and false negatives

Final Outcome

Successfully trained a Logistic Regression model

Understood the importance of train-test splitting

Learned how to evaluate classification models

Gained hands-on experience with real ML metrics# Task5-traintestsplit
