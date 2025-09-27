# 🫀 Heart Disease Prediction & Analysis using ML
## 🌟 Project Overview

This project predicts heart disease risks using Machine Learning.
It covers the full pipeline: data cleaning, feature selection, PCA, model training, evaluation, clustering, and hyperparameter tuning.

## 🎯 Objectives

  - Clean and preprocess data

  - Reduce dimensions using PCA

  - Select important features

  - Train classification models: Logistic Regression, Decision Tree, Random Forest, SVM

  - Apply clustering: K-Means & Hierarchical

  - Optimize models with Hyperparameter Tuning

## 📊 Dataset

- Source: [Heart Disease UCI Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)

- Content: Medical attributes like age, sex, blood pressure, cholesterol, and heart-related features to predict heart disease.


## 🧩 Project Workflow
### 1️⃣ Data Preprocessing & Cleaning

  - Handle missing values

  - Encode categorical variables

  - Standardize numerical features

  - EDA with histograms, boxplots, correlation heatmaps

✅ Deliverable: Clean dataset ready for modeling





### 2️⃣ Dimensionality Reduction (PCA)

  - Reduce feature dimensions with PCA

  - Select optimal number of components

  - Visualize variance and components

✅ Deliverable: PCA-transformed dataset + plots



### 3️⃣ Feature Selection

  - Rank features using Random Forest/XGBoost

  - Apply RFE

  - Check significance with Chi-Square

✅ Deliverable: Key features + importance visualization



### 4️⃣ Supervised Learning - Classification

  - Split data: 80% train / 20% test

  - Train: Logistic Regression, Decision Tree, Random Forest, SVM

  - Evaluate: Accuracy, Precision, Recall, F1-score, ROC & AUC

✅ Deliverable: Trained models + evaluation metrics



### 5️⃣ Unsupervised Learning - Clustering

  - K-Means (use elbow method to find K)

  - Hierarchical Clustering (dendrograms)

  - Compare clusters with actual labels

✅ Deliverable: Clustering models + visualizations



### 6️⃣ Hyperparameter Tuning

  - Optimize models with GridSearchCV & RandomizedSearchCV

  - Compare with baseline performance

✅ Deliverable: Best model with tuned hyperparameters
