# Data-Mining-Project

## Dataset: 🧠 Alzheimer's Disease Dataset 🧠. https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset The dataset would interest me because it has enough data for me to look through and work with it. 

## Problem Definition and Data Acquisition: Using the deatset to predict Alzheimer Disease. Alzheimer disease is a growing concern for a long time now. I want to predict like if it can be genetics, medical history or age.

## Target: Alzheimer Disease

## I want to predict how Alzheimer diesease will happen. Based on right now on research I want to conclude the prediction by age. (Subject to change). 

## I chose the 🧠 Alzheimer's Disease Dataset 🧠 from Kaggle because it has over 500 features and the dataset is recent. It interest me because I wanted to know more about Alzheimer's disease so it is a good oppertunity for me to learn. 

## The value of the model is promising because the decision model can help with making predcitions, accuracy and find patterns that are helpful.

## Updated Readme

### 

Alzheimer’s Disease Prediction
Overview

This project uses machine learning to predict Alzheimer’s disease based on patient health, lifestyle, demographic, and clinical data. The goal is to compare a full clinical model with an early-risk model and identify key predictive features.

Dataset
2,149 patient records, 35 features
No missing data
Target: Diagnosis (0 = No, 1 = Yes)
Class balance: ~65% No, ~35% Yes
Models

Random Forest Classifier

Full Clinical Model
Uses all features (including MMSE, ADL, Functional Assessment)
Accuracy: ~94%
Limitation: possible data leakage (features tied to diagnosis)
Early-Risk Model
Removes clinical testing features
Uses lifestyle, health, and symptom data
Accuracy: ~65–67%
More realistic for early prediction
Key Results
Full model performed best but relied heavily on clinical features
Early model showed that prediction is harder without clinical testing
Important features included:
MemoryComplaints
BehavioralProblems
SleepQuality
BMI
AlcoholConsumption
Evaluation
Accuracy, Precision, Recall, F1-score, ROC-AUC
Accuracy alone is limited due to class imbalance
Limitations & Ethics
Class imbalance may bias predictions
Demographic variables may introduce fairness issues
False negatives are critical in medical predictions
Clinical features may inflate model performance
