🧠 Autism Prediction Model

This project builds a machine learning model to predict the likelihood of Autism Spectrum Disorder (ASD) based on questionnaire responses and related features.

📘 Overview

Algorithm: RandomForestClassifier

Goal: Classify whether an individual is likely to be autistic (1) or not (0).

Dataset: Publicly available Autism Screening Dataset (source: Kaggle)

🔧 Best Model
RandomForestClassifier(
    max_depth=10,
    min_samples_leaf=2,
    min_samples_split=10,
    n_estimators=50,
    random_state=42
)


Best Cross-Validation Accuracy: 0.87

📊 Evaluation Results

Accuracy: 0.8375

Confusion Matrix:

[[115   9]
 [ 17  19]]


Classification Report:

              precision    recall  f1-score   support
0                 0.87      0.93      0.90       124
1                 0.68      0.53      0.59        36

🏁 Kaggle Submission

Score: 0.68996

Public Score: 0.64722