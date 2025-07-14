# 📊 Data Analysis & Machine Learning Projects

This repository contains two structured assignments focused on:

- **Exploratory Data Analysis (EDA)** using a synthetic employee dataset.
- **Predictive Modeling** using Linear Regression on a housing dataset.

Each assignment is implemented in Python with clear documentation, reproducible steps, and industry-standard libraries.

---

## 📁 Repository Structure

├── SET4_Employee_Analysis/
│ ├── synthetic_employee_dataset.csv
│ ├── employee_analysis.ipynb
│
├── SET5_Housing_Price_Prediction/
│ ├── housing.csv
│ ├── housing_price_prediction.ipynb
│
└── README.md

## 🔍 Assignment 1 — Employee Dataset Exploration (SET 4)

### 📌 Objective

Perform a comprehensive univariate analysis on employee data to uncover patterns, distributions, and basic statistics.

### 📂 Dataset

- **File:** `synthetic_employee_dataset.csv`
- **Type:** Tabular data (synthetic)
- **Contents:** Employee attributes such as department, salary, experience, etc.

### ✅ Task Breakdown

1. Display the **first 10 rows** of the dataset.
2. Show **complete dataset information**, including:
   - Column names and data types
   - Null values (if any)
3. Display the **number of rows and columns**.
4. Perform **univariate analysis**, including:
   - Descriptive statistics for numerical features
   - Value counts for categorical features
   - Distribution plots (histograms, KDE plots)
   - Frequency analysis of dominant values

### 🛠️ Libraries Used

- `pandas` – data handling
- `matplotlib`, `seaborn` – visualization

---

## 🏡 Assignment 2 — Housing Price Prediction (SET 5)

### 📌 Objective

Build and evaluate a **Linear Regression** model to predict housing prices based on multiple features.

### 📂 Dataset

- **File:** `housing.csv`
- **Type:** Tabular data
- **Contents:** Housing features (e.g., square footage, number of rooms, location) and target variable (price)

### ✅ Implementation Steps

1. Load the dataset with proper **validation checks** (e.g., missing values, data types).
2. Split the dataset into **training and testing sets** using an 80-20 or 70-30 ratio.
3. Train a **Linear Regression** model using `scikit-learn`.
4. Evaluate the model using:
   - **R² Score**: Goodness of fit
   - **Mean Squared Error (MSE)**: Prediction error magnitude

### 🛠️ Libraries Used

- `pandas`, `numpy` – data processing
- `scikit-learn` – model training and evaluation
-  
---
