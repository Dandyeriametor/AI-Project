# AI-Project
Fraud Detection Using Machine Learning
Anomaly Detection with Random Forest (Google Colab Project)

This project applies machine learning techniques to detect fraudulent online transactions using an imbalanced fraud dataset. The goal is to build, evaluate, and deploy a fraud detection model entirely in Google Colab, following end-to-end AI development best practices.

Project Overview

Online fraud is a significant real-world challenge. Fraudulent transactions are rare (anomalies), making detection difficult.
This project uses a dataset (Fraud Detection.csv) containing transaction details and a binary target indicating whether an activity is fraudulent.

The pipeline includes:

Data cleaning & preprocessing

Exploratory data analysis

Handling imbalance

Model training with Random Forest

Hyperparameter tuning via GridSearchCV

Model evaluation and visualization

Deployment-ready prediction function

Files in This Repository
File	Description
fraud_detection_project_colab.ipynb	Main notebook containing the full workflow (data prep → modeling → evaluation → deployment).
Fraud Detection.csv	Dataset used for the project (upload in Colab before running).
Fraud_Detection_Project_Report.docx	Final written report summarizing methods, results, and deployment.

Features Implemented

Preprocessing

Renaming inconsistent columns

Dropping ID-like variables

Encoding categorical features

Scaling numeric features

Modeling

Random Forest with class imbalance handling

Hyperparameter tuning using AUC-scored GridSearchCV

End-to-end Scikit-learn pipeline

Evaluation

Accuracy, Precision, Recall, F1

Confusion Matrix

ROC Curve & AUC

Feature Importance Bar Chart

Deployment

A reusable function:

predict_transaction(model, sample_dict)


Accepts user input and outputs "Fraud" or "Safe" with confidence.

 How to Run the Project (Google Colab)

Open the notebook (fraud_detection_project_colab.ipynb) in Google Colab.

Upload Fraud Detection.csv when prompted.

Run all cells from top to bottom.

Use the final prediction function to classify new transactions.

 Requirements

The notebook installs necessary packages automatically, but key libraries include:

pandas

numpy

scikit-learn

matplotlib

seaborn

 Author: Dandy Eriametor

This project was completed as part of an AI/ML coursework assignment focused on anomaly detection and real-world machine learning deployment.
