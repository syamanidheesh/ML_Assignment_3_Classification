# 🧠 ML Assignment 3 – Classification

## 📋 Objective
The objective of this assessment is to evaluate the understanding and ability to apply **supervised learning techniques** to a real-world dataset.  
This project focuses on implementing and comparing various classification algorithms on the **Breast Cancer dataset** available in Scikit-learn.

---

## 📊 Dataset
The **Breast Cancer dataset** from the `sklearn.datasets` library is used in this project.  
It contains features derived from digitized images of fine needle aspirates (FNA) of breast masses and aims to classify tumors as **malignant** or **benign**.

**Dataset Details:**
- Samples: 569
- Features: 30 numeric features
- Classes: 2 (Malignant, Benign)
- Source: `sklearn.datasets.load_breast_cancer()`

---

## ⚙️ Data Loading and Preprocessing

### Steps Performed:
1. **Data Loading:** Loaded the dataset using Scikit-learn.
2. **Missing Values:** Checked for null values — none found.
3. **Feature Scaling:** Applied `StandardScaler` to normalize features.


---

## 🤖 Classification Algorithms Implemented

| No. | Algorithm | Description |
|-----|------------|-------------|
| 1 | **Logistic Regression** | A linear model that estimates probabilities using the logistic function. Ideal for binary classification. |
| 2 | **Decision Tree Classifier** | Builds a tree-like structure of decisions based on feature values. Can overfit if not pruned. |
| 3 | **Random Forest Classifier** | An ensemble of decision trees that improves performance by reducing overfitting. |
| 4 | **Support Vector Machine (SVM)** | Finds the optimal hyperplane that maximizes class separation. Works well with high-dimensional data. |
| 5 | **k-Nearest Neighbors (k-NN)** | Classifies a data point based on the majority vote of its nearest neighbors. Simple yet effective. |

---

## 📈 Model Comparison

| Algorithm | Accuracy | Remarks |
|------------|-----------|----------|
| **Logistic Regression** | **98%** | **Best performing model** |
| Decision Tree | 93% | Slight overfitting tendency |
| Random Forest | 96% | Stable and robust performance |
| Support Vector Machine (SVM) | 97% | Performs well in high-dimensional space |
| k-Nearest Neighbors | 96% | Performs well but sensitive to scaling |

> 🏆 **Best Performing Model:** Logistic Regression  
> ⚠️ **Least Performing Model:** Decision Tree Classifier (due to overfitting)

