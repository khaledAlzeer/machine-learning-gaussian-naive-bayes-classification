# 🧠 Gaussian Naive Bayes – Social Network Ads Classification

## 📖 Project Overview
This project demonstrates the implementation of the **Gaussian Naive Bayes** classification algorithm using Python and Scikit-Learn.

The goal is to predict whether a user will purchase a product based on:

- Age
- Estimated Salary

The dataset used is **Social_Network_Ads.csv**.

---

## ⚙️ Machine Learning Workflow

The project follows a standard ML pipeline:

1. Importing the libraries
2. Importing the dataset
3. Splitting the dataset into Training and Test sets
4. Feature Scaling (used for visualization purposes)
5. Training the Gaussian Naive Bayes model
6. Predicting new results
7. Evaluating performance using:
   - Confusion Matrix
   - Accuracy Score
8. Visualizing:
   - Training set results
   - Test set results

---

## 🤖 Algorithm Used

Gaussian Naive Bayes

Why GaussianNB?

- Suitable for continuous numerical features
- Assumes features follow a normal (Gaussian) distribution
- Fast and computationally efficient
- Works well even with small datasets

---

## 📊 Model Evaluation

The model performance is evaluated using:

- Confusion Matrix
- Accuracy Score

The decision boundary is also visualized to better understand how the classifier separates the classes.

---

## 📁 Dataset Features

| Feature | Description |
|----------|-------------|
| Age | User's age |
| EstimatedSalary | User's estimated salary |
| Purchased | Target variable (0 = No, 1 = Yes) |

---

## 🚀 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---
