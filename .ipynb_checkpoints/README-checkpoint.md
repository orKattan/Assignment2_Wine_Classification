🧪 Wine Classification using KNN & PCA
This project implements a full machine learning pipeline to classify wine samples based on their chemical properties. The goal is to distinguish between three different wine cultivars using a supervised learning approach.

📁 Dataset
Based on the UCI Wine Recognition Dataset
13 numeric features such as alcohol, proline, flavanoids, etc.
Target: wine class (0, 1, or 2)
🚀 Pipeline Overview
Data Loading

Load training and test data from CSV files (wine_train.csv, wine_test.csv)
Preprocessing

Separate features from the target
Normalize features using StandardScaler
Model Selection

Use GridSearchCV to find the optimal k value for KNN (1 to 20)
Model Evaluation

Evaluate performance on a validation split
Evaluate on a separate test set
Display classification report and confusion matrix
Visualization with PCA

Apply PCA to reduce feature dimensions to 2D
Create a scatter plot of the PCA-transformed training set
📊 Technologies Used
Python
pandas, NumPy
scikit-learn
matplotlib, seaborn
📈 Example Output
A 2D PCA projection graph showing wine class separation.

👤 Author
Or Kattan
Student ID: 211312657
Course: Machine Learning – Assignment 2