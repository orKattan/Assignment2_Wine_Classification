# 🍷 Wine Classification using KNN & PCA

This project implements a full machine learning pipeline to classify wine samples based on their chemical properties.  
The goal is to distinguish between three different wine cultivars using a supervised learning approach.

---

## 📁 Dataset
- Based on the **UCI Wine Recognition Dataset**
- 13 numeric features (e.g., alcohol, proline, flavanoids, etc.)
- Target: wine class (0, 1, or 2)

---

## 🚀 Pipeline Overview

### 1. Data Loading
- Load training and test data from CSV files (`wine_train.csv`, `wine_test.csv`)

### 2. Preprocessing
- Separate features from the target
- Normalize features using `StandardScaler`

### 3. Model Selection
- Use `GridSearchCV` to find the optimal `k` value for KNN (range 1–20)

### 4. Model Evaluation
- Evaluate performance on a validation split
- Evaluate on a separate test set
- Display classification report and confusion matrix

### 5. Dimensionality Reduction with PCA
- Apply PCA to reduce feature dimensions to 2D
- Create a scatter plot of the PCA-transformed training set

---

## 📊 Example Output
- A 2D PCA projection graph showing wine class separation

---

## 🛠️ Technologies Used
- Python
- `pandas`, `NumPy`, `scikit-learn`, `matplotlib`, `seaborn`

---

## 👤 Author
- Or Kattan  
- Student ID: 211312657  
- Course: Machine Learning – Assignment 2  
- Repo: `Assignment2_Wine_Classification`