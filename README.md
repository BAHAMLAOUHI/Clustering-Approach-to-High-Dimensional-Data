# Clustering Approach to High-Dimensional Data

This repository is dedicated to exploring effective clustering approaches for high-dimensional data. Our primary objective is to find clustering techniques that provide meaningful labels, which can then be used to enhance downstream classification tasks.

---

## Dataset

The dataset used in this study is the **UCI (University of California, Irvine) "Default of Credit Card Clients" dataset**. It includes information on client demographics, financial behaviors, and payment history, making it ideal for clustering and classification experiments.

---

## Project Goals

1. **Clustering High-Dimensional Data:**
   - Explore and evaluate different clustering techniques to generate meaningful group labels for the dataset.
2. **Classification Using Cluster Labels:**
   - Test the quality of the generated labels by using them as a target variable in classification models.

---

## Project Workflow

### 1. **EDA and Preprocessing**
  - Understand the dataset through exploratory data analysis (EDA).
  - Preprocess the data for clustering by handling missing values, scaling features, and encoding categorical variables.


### 2. **Clustering Techniques**
  - Apply and evaluate various clustering algorithms to group the dataset effectively.
- **Algorithms Explored:**
  - **K-Means Clustering**
  - **Fuzzy C-Means Clustering**
  - **Spectral Clustering**
  - **K-Medoids Clustering**
  - Comparison of clustering methods to identify the most suitable approach for high-dimensional data.

### 3. **Classification Models**

  - Validate the quality of clustering labels by using them as the target variable in classification tasks.
- **Classification Algorithms:**
  - **Random Forest Classifier (RFC)**
  - **Decision Tree Classifier (DTC)**
  - **XGBoost (XGB)**
  - **Gaussian Naive Bayes (GNB)**
  - **K-Nearest Neighbors (KNN)**

  - Evaluation metrics such as Accuracy, F1 Score, and Precision to assess classification performance.

---

## Results Summary

- **Clustering Techniques:** Spectral Clustering consistently demonstrated the most meaningful results, leading to better classification performance.
- **Classification Models:** Random Forest and XGBoost performed best when using Spectral Clustering labels.

---



 
