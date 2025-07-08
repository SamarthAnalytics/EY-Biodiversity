EY Biodiversity Challenge – Frog Presence Classification
Team Members:

Samarth Verma

Haeun Kim

Jayasree Lakshmi Narayanan

#Project Overview
This project focuses on predicting frog presence in specific ecosystems using environmental and climate data. The dataset included features such as temperature, precipitation, vapor pressure deficit, and soil type. The objective was to build an accurate classification model that supports biodiversity conservation efforts.

#Problem Statement
Binary Classification: Predict frog presence (1) or absence (0)

Imbalance: The dataset was highly imbalanced (Presence: 3,792 vs Absence: 2,520)

#Data Preprocessing
Feature Selection: Chose relevant features using domain knowledge and correlation analysis

Outlier Handling: Z-score method applied to minimize the effect of extreme values

Balancing: Used RandomOverSampler to balance the target variable classes

#Models Explored
LightGBM

XGBoost

ExtraTreesClassifier (Final model)

#Final Model Performance
Model: ExtraTreesClassifier

<img width="409" alt="Screenshot 2025-07-08 at 10 22 17 AM" src="https://github.com/user-attachments/assets/a337ea85-1abf-417f-8bea-5f530a9a9586" />

Test Accuracy: 83.1%

F1 Score: 0.83

Chosen for: Strong generalization and minimal overfitting

##Key Learnings
Hyperparameter tuning significantly boosts performance

Ensemble methods outperform gradient boosting in this case

Preprocessing (balancing, feature refinement, and outlier removal) is crucial for model success

