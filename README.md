# 🏥 Medical Insurance Cost Prediction using Linear Regression

## 📌 Project Overview

This project predicts **medical insurance charges** based on personal and lifestyle attributes using **Linear Regression**. It demonstrates a complete **end-to-end Machine Learning workflow**, implemented and executed in **Google Colab**, and version-controlled using **GitHub**.

The project covers:

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Model training
* Model evaluation
* Interpretation of results
* User input–based prediction

---

## 🎯 Problem Statement

Medical insurance costs vary significantly based on individual characteristics such as age, BMI, and smoking habits. The goal of this project is to:

> **Build a regression model that accurately predicts insurance charges for a given individual.**

---

## 📂 Dataset Information

* **Dataset Name:** Medical Cost Personal Dataset
* **Source:** Kaggle
* **Target Variable:** `charges`

### 🔑 Features Used

| Feature    | Description             |
| ---------- | ----------------------- |
| `age`      | Age of the individual   |
| `sex`      | Gender (male/female)    |
| `bmi`      | Body Mass Index         |
| `children` | Number of dependents    |
| `smoker`   | Smoking status (yes/no) |
| `region`   | Residential region      |

---

## 🛠️ Tools & Technologies

* **Language:** Python
* **Platform:** Google Colab
* **Libraries:**

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

The following EDA steps were performed:

* Dataset shape and data type inspection
* Missing value analysis
* Distribution analysis of numerical features
* Categorical feature analysis
* Correlation analysis using heatmap

📌 EDA revealed that **smoking status, age, and BMI** strongly influence insurance charges.

---

## ⚙️ Data Preprocessing

* Converted categorical variables using **One-Hot Encoding**
* Selected relevant features
* Split data into **training and testing sets**
* Ensured compatibility between training and prediction inputs

---

## 🤖 Model Building

* **Algorithm Used:** Linear Regression
* **Why Linear Regression?**

  * Simple and interpretable
  * Suitable for continuous target prediction
  * Helps understand feature impact on insurance cost

The model was trained using Scikit-learn’s `LinearRegression`.

---

## 📊 Model Evaluation

The model performance was evaluated using:

* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

📈 The model achieved an **R² score of ~0.75–0.80**, indicating good predictive performance.

### 📉 Visual Evaluation

* Actual vs Predicted Charges plot
* Residual plot to check error distribution

---

## 🧠 Model Interpretation

Regression coefficients were analyzed to understand feature influence.

### 🔑 Key Insights

* **Smoking status** has the highest positive impact on insurance charges
* **Age** and **BMI** significantly increase predicted costs
* **Region** and **number of children** have minimal influence

This makes the model highly interpretable and suitable for business insights.

---

## 🧑‍💻 User Input Prediction

The project includes a **command-line style user input prediction** feature, allowing users to enter personal details and get predicted insurance charges using the trained model.




