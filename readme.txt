🩺 Diabetes Prediction Project
📌 Overview

This project focuses on predicting diabetes using machine learning models.
We worked with a public dataset and applied different algorithms to compare their performance.

🚀 What We Did

Preprocessed the dataset (handling missing values, scaling features).

Split the data into training and testing sets.

Built and tuned three models using GridSearchCV:

Logistic Regression

Random Forest

Support Vector Machine (SVM)

Evaluated models using ROC-AUC and compared results.

Visualized:

Feature importances (Random Forest)

Coefficient magnitudes (Logistic Regression & Linear SVM)

Selected the best-performing model.

Saved the final pipeline (best_diabetes_pipeline.joblib) for future use.

🛠 Tech Stack

Python

scikit-learn

pandas

seaborn & matplotlib

📊 Goal

To identify the most suitable machine learning model for diabetes prediction and provide a reusable pipeline.