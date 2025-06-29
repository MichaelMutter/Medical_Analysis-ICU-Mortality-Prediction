# Medical Data Analysis & ICU Mortality Prediction

This project analyzes ICU patient data to predict in-hospital mortality using a combination of unsupervised and supervised machine learning techniques. The data is based on a sample from the MIMIC-III clinical database.

## 📌 Overview

The notebook includes the following steps:

1. **Data Preprocessing**
   - Handling missing values
   - Feature engineering and encoding
   - Creation of derived features such as ICU length of stay and severity scores

2. **Unsupervised Learning**
   - Clustering patients using K-Means
   - Dimensionality reduction with PCA
   - Cluster assignment added as features to downstream models

3. **Supervised Learning**
   - Model training and evaluation using:
     - XGBoost
     - Neural Network (Keras)
     - Random Forest
     - Logistic Regression
   - Performance metrics: AUC, recall, precision, classification report
   - Feature importance analysis (for tree-based models)
   - Threshold optimization (for neural network)

4. **Visualization**
   - ROC curves
   - Feature importance plots
   - Cluster distribution analysis

## 📂 Files

- `Medical_Analysis_Mini_Project.ipynb` – Main analysis notebook
- `README.md` – Project description

