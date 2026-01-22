# 🧠 Brain Stroke Prediction — Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on a healthcare dataset to understand the key health and lifestyle factors associated with **stroke occurrence**.

The goal is to clean, analyze, and visualize the dataset before applying any machine learning models.

---

## 📌 Dataset Information

- **Dataset:** Healthcare Stroke Prediction Dataset
- **Source:** Kaggle
- **Rows:** 5110
- **Columns:** 12
- Contains patient details such as:
  - Age
  - BMI
  - Average Glucose Level
  - Hypertension
  - Heart Disease
  - Smoking Status
  - Work Type
  - Stroke (Target Variable)

---

## 🎯 Objective of the Project

- Perform data cleaning and preprocessing
- Handle missing values, duplicates, and outliers
- Perform Univariate, Bivariate, and Multivariate analysis
- Create pivot tables for deeper insights
- Identify key factors contributing to stroke

---

## 🧹 Data Cleaning & Preparation

- Found missing values in **BMI (~3.93%)**
- Filled missing BMI values using **median**
- Checked for duplicate records (none found)
- Detected outliers using **IQR method**
- Identified **class imbalance** in stroke cases

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Age distribution
- BMI distribution
- Stroke count distribution

### 🔹 Bivariate Analysis
- Hypertension vs Stroke
- Heart Disease vs Stroke

### 🔹 Multivariate Analysis
- Average Glucose Level vs Stroke (Boxplot)

### 🔹 Pivot Tables
- Work Type vs Stroke
- Smoking Status vs Stroke

---

## 🔍 Key Insights

- Stroke cases are more common in elderly individuals
- Hypertension and heart disease significantly increase stroke risk
- Higher glucose levels are observed in stroke patients
- Smokers show higher stroke occurrence
- Proper data cleaning was required before analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
