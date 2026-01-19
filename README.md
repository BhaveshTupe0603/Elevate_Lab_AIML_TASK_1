# 📊 Data Analysis & ML Readiness Assessment

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📝 Project Overview
This repository contains the analysis for **Task 1: Understanding Dataset & Data Types**. 

The goal of this project was to load, inspect, and analyze two distinct datasets (**Titanic** and **Students Performance**) to determine their structure, data types, and readiness for Machine Learning models.

## 📂 Datasets Analyzed
1.  **Titanic Dataset:** Used for Binary Classification (predicting survival).
2.  **Students Performance Dataset:** Used for Regression/Analysis (predicting scores).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Seaborn
* **Environment:** Google Colab / Jupyter Notebook

## 🔍 Key Activities & Insights

### 1. Data Structure Analysis
* Loaded datasets using `pandas`.
* Inspected rows/columns using `head()`, `tail()`, and `shape`.
* **Observation:** The Titanic dataset contains **891 rows** and **15 columns**.

### 2. Feature Identification
* Classified features into **Numerical** (e.g., Age, Fare), **Categorical** (e.g., Sex, Embarked), and **Ordinal** (e.g., Class).
* Identified the **Target Variable** for ML: `survived` (0/1).

### 3. Data Quality Check
* **Missing Values:** Detected significant missing data in the `deck` column (~77%) and `age` column (~20%).
* **Imbalance:** Noted a 61% (died) vs 38% (survived) distribution in the target variable.

## 📈 Conclusion
The Titanic dataset is **partially ready** for Machine Learning. 
* **Action Plan:** The `age` column requires imputation (filling missing values), and categorical columns (like `sex`) need encoding before training a model.

---
*Created as part of the Data Science Internship Task 1.*
