# Breast-Cancer-Prediction-using-K-Nearest-Neighbors-KNN

# 📋 Project Overview:
This project aims to predict whether a tumor is benign or malignant using the Breast Cancer Wisconsin dataset and the K-Nearest Neighbors (KNN) algorithm. The project includes both the machine learning backend and a Streamlit frontend where users can input tumor characteristics and get real-time predictions.

# 🔍 Dataset:
The dataset used in this project is the Breast Cancer Wisconsin dataset, which consists of several numerical features representing characteristics of tumors, such as:

Clump Thickness
Uniformity of Cell Size
Uniformity of Cell Shape
Marginal Adhesion
Single Epithelial Cell Size
Bare Nuclei
Bland Chromatin
Normal Nucleoli
Mitoses
The target variable (Class) indicates whether a tumor is benign (2) or malignant (4).

# Features:
## Machine Learning Model:
The project uses a K-Nearest Neighbors (KNN) classifier to predict the tumor class (benign or malignant).
## Frontend Application: 
A user-friendly web app built with Streamlit, where users can input tumor characteristics and receive predictions in real-time.
## Model Tuning:
The project explores different values of k (3 to 9) to find the optimal KNN model configuration.

# Project Components:
  ## Data Preprocessing:
  * Handling missing values using median imputation.
  * Feature scaling using StandardScaler.
  * Splitting the dataset into 80% training and 20% testing sets.

  ## K-Nearest Neighbors (KNN) Model:
   * A KNN classifier is built using different values of k, with the best results achieved using k=6, k=7, and k=8.
   * Confusion Matrix, Accuracy, Precision, Recall, and F1-Score are used to evaluate model performance.

 ## Streamlit Frontend:
  * A simple interface where users can input features like clump thickness, cell size/shape uniformity, bare nuclei, etc.
  * The app then predicts whether the tumor is benign or malignant using the saved KNN model.















