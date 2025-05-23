Comparative Analysis of ML Algorithms for Fetal Health Prediction
This project presents a comparative study of various machine learning algorithms to predict fetal health status using Cardiotocogram (CTG) data.The objective is to improve early detection of fetal complications and support clinicians in making data-driven decisions.

 Project Overview:
 Objective: Classify fetal health into Normal, Suspect, or Pathological categories using CTG data.
Algorithms Used:
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Random Forest (RF)
Gradient Boosting (GB)
Best Accuracy: 96.92% achieved using Gradient Boosting

Dataset:
Source: Kaggle
Records: 2113
Features include: baseline fetal heart rate, accelerations, fetal movements, uterine contractions, etc.

Methodology:

Data Preprocessing & Cleaning
Exploratory Data Analysis (EDA)
Feature Selection with SelectKBest
Model Training & Evaluation
Comparison using Accuracy, Precision, Recall, and F1-score

Results
Gradient Boosting outperformed all other models with the highest testing accuracy and minimal error margin. 
Proper handling of class imbalance and hyperparameter tuning were key factors
