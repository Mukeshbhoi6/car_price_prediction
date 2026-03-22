# Car Price Prediction using Machine Learning

##  Project Overview

This project predicts the selling price of used cars using Machine Learning techniques. The goal is to build an accurate regression model by applying data preprocessing, feature engineering, and model optimization techniques.

---

## Problem Statement

To predict the **selling price of a car** based on various features such as:

* Present Price
* Kms Driven
* Fuel Type
* Seller Type
* Transmission
* Owner
* Age of Car

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## Steps Performed

### 1️⃣ Data Preprocessing

* Removed unnecessary columns (e.g., Car Name)
* Handled duplicates and missing values
* Converted categorical data using Label Encoding

### 2️⃣ Feature Engineering

* Created new feature: **Age of Car**
* Applied **Log Transformation** on skewed features
* Generated **Polynomial Features** to capture non-linear relationships

### 3️⃣ Feature Scaling

* Used MinMaxScaler to normalize data

### 4️⃣ Feature Selection

* Used **f_regression** to evaluate feature importance
* Selected features based on:

  * High F-score
  * Low p-value

### 5️⃣ Model Building

* Applied **Linear Regression**
* Improved model using **Polynomial Regression**

### 6️⃣ Model Evaluation

* Used metrics:

  * MAE (Mean Absolute Error)
  * MSE (Mean Squared Error)
  * R² Score
* Performed **Cross Validation**
* Tested multiple train-test splits

---

##  Results

* Best Test R² Score: **0.94**
* Significant improvement after applying polynomial features and feature selection
* Reduced error (MAE, MSE) compared to basic model

---

##  Key Insights

* Polynomial features helped capture non-linear relationships
* Feature selection improved model performance and reduced overfitting
* Log transformation handled skewed data effectively

---

##  How to Run

1. Clone the repository
2. Install required libraries
3. Run the Jupyter Notebook

---
