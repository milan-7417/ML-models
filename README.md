

# Salary Prediction Model

## 📌 Overview

This project predicts employee salaries based on features such as **Age**,  and other attributes using **Multiple Linear Regression** in Python.
It is part of the **ML-models** repository and demonstrates a complete end-to-end machine learning workflow — from preprocessing to evaluation.

---

## 📂 Dataset

**Example columns:**

* `Name` (removed from modeling)
* `Age`
* 'City'
* `Salary` (target)

**Preprocessing Steps:**

* Dropped `Name` column
* Converted categorical features to numeric values (if present)
* Applied feature scaling for better model performance

---

## 🛠️ Technologies Used

* **Python 3.x**
* **pandas** — data manipulation
* **NumPy** — numerical operations
* **Matplotlib & Seaborn** — visualization
* **scikit-learn** — model building & evaluation

---

## 📊 Project Workflow

1. **Data Preprocessing**

   * Removing irrelevant columns (`Name`)
   * Handling missing values
   * Feature encoding and scaling

2. **Model Building**

   * Multiple Linear Regression using `sklearn.linear_model.LinearRegression`
   * Splitting dataset into **train** and **test** sets

3. **Evaluation**

   *Mean absolute percentage error to measure model accuracy
   * Visualizing feature vs. salary relationships
