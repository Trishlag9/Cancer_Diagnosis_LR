# 🧪 Cancer Diagnosis Prediction using Logistic Regression

This project applies a **logistic regression** model to predict whether a tumor is benign or malignant based on various features from a breast cancer dataset.

## 📁 Dataset

- Source: Breast Cancer Wisconsin (Diagnostic) Dataset
- Format: CSV file with 569 rows and 33 columns
- Target Variable: `diagnosis` (B = Benign, M = Malignant)

## 🛠️ Steps Performed

1. Loaded and explored the dataset
2. Preprocessed and encoded categorical data
3. Normalized features using StandardScaler
4. Split the data into training and testing sets
5. Built a **Logistic Regression model**
6. Evaluated accuracy and performance metrics

## ✅ Results

- **Accuracy**: 98%
- High **Precision**, **Recall**, and **F1-score** for both classes
- Model is well-suited for binary classification tasks

## 📊 Libraries Used

- pandas, seaborn, matplotlib
- scikit-learn (for model, metrics, preprocessing)

## 📌 How to Run

Run `LogisticRegression.ipynb` in any Jupyter environment. Dataset should be placed in the same directory or update the file path accordingly.

---

