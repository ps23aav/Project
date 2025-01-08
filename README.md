# Chronic Kidney Disease Prediction Using Machine Learning

This repository contains a machine learning project aimed at predicting Chronic Kidney Disease (CKD) using various machine learning models. The project implements and evaluates multiple algorithms, including Random Forest, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Gradient Boosting (XGBoost), and Artificial Neural Networks (ANN). 

The dataset used for this study is synthetic and includes key clinical, demographic, and behavioral attributes related to CKD. The project applies data preprocessing techniques, class balancing using SMOTE, and comprehensive model evaluation to determine the best-performing algorithm.

---

## Features
- *Data Preprocessing*: 
  - Handles missing values using mean and mode imputation.
  - Encodes categorical variables using LabelEncoder.
  - Applies feature scaling using StandardScaler.

- *Class Balancing*: 
  - Balances the dataset using SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance.

- *Algorithms Evaluated*:
  - Random Forest
  - Logistic Regression
  - Support Vector Machines (SVM)
  - K-Nearest Neighbors (KNN)
  - Gradient Boosting (XGBoost)
  - Artificial Neural Network (ANN)

- *Performance Metrics*:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix

- *Visualization*:
  - Data distribution plots.
  - Feature importance from Random Forest.
  - 2D visualization of the balanced dataset using PCA.

- *Model Testing*:
  - Predicts CKD status for randomly selected rows from the dataset.
  - Compares predictions with actual results.

---

## Installation

To run this project locally, follow these steps:

1. *Clone the Repository*:
   ```bash
   git clone https://github.com/ps23aav/Project/tree/main

   cd CKD_Prediction
2. *Install Dependencies*: 
Install required Python libraries:
```bash
pip install -r requirements.txt

3. *Set Up the Dataset*:
Place the Chronic_Kidney_Dsease_data.csv file in the root directory or specify the correct path in the code.
