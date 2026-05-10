# ❤️ Heart Disease Classifier

A Machine Learning project that predicts the presence of heart disease based on medical and clinical patient data.

---

## 📌 Dataset Overview
The dataset contains 303 patient records with 15 features including:
- Age
- Sex
- Chest Pain Type
- Blood Pressure (RestBP)
- Cholesterol (Chol)
- Maximum Heart Rate (MaxHR)
- Oldpeak
- And other medical attributes

Target column:
- **AHD (Heart Disease presence)**

---

## 🚀 Project Goal
To build a classification model that can predict whether a patient has heart disease or not using different machine learning algorithms.

---

## 📊 Features
- Data cleaning and handling missing values
- Exploratory Data Analysis (EDA)
- Encoding categorical features
- Model training and comparison
- Performance evaluation

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Machine Learning Models Used
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📂 Dataset Info
- Number of samples: 303
- Number of features: 15
- Missing values:
  - Ca column has missing values
  - Thal column has missing values
- Target variable: AHD

---

## 📈 Workflow
1. Load dataset using Pandas
2. Explore data using `df.info()`
3. Handle missing values
4. Encode categorical variables
5. Split dataset into training and testing sets
6. Train multiple ML models
7. Evaluate models using:
   - Confusion Matrix
   - Classification Report
