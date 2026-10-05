# Telco Customer Churn — Regression Analysis

## 📌 Project Overview

This project focuses on **Regression Analysis of Telco Customer data** using Python and Scikit-learn.

The notebook applies **Simple Linear Regression** and **Multiple Linear Regression** to analyze the relationship between customer information and **TotalCharges**.

The main purpose of this project is to understand how regression techniques can be applied to a real-world customer dataset, perform predictions, and interpret the results.

> **Note:** This is an educational and analytical project focused on understanding regression techniques. It is not a production-ready Machine Learning model or deployed prediction system.

---

## 🎯 Objective

The main objective of this project is to:

* Analyze the Telco Customer dataset
* Inspect and prepare numerical data
* Understand relationships between variables
* Apply Simple Linear Regression
* Apply Multiple Linear Regression
* Generate regression predictions
* Evaluate regression results
* Visualize and interpret the analysis

> **Note:** The `Churn` column represents a Yes/No classification outcome. In this project, `Churn` is not used as the regression target. The target variable is `TotalCharges`.

---

## 📊 Regression Analysis

### 1. Simple Linear Regression

Simple Linear Regression is used to understand the relationship between a single independent variable and `TotalCharges`.

In this project, **customer tenure** is analyzed in relation to total charges.

```text
TotalCharges = β₀ + β₁ × tenure
```

The analysis helps understand how changes in customer tenure are associated with changes in total charges.

### 2. Multiple Linear Regression

Multiple Linear Regression is used to analyze `TotalCharges` using multiple numerical variables.

```text
TotalCharges = β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ
```

This provides a broader understanding of how multiple numerical factors are associated with a customer's total charges.

---

## 📊 Dataset

The dataset contains information about telecommunications customers.

Some important features include:

* `customerID`
* `gender`
* `SeniorCitizen`
* `Partner`
* `Dependents`
* `tenure`
* `PhoneService`
* `MultipleLines`
* `InternetService`
* `OnlineSecurity`
* `OnlineBackup`
* `DeviceProtection`
* `TechSupport`
* `StreamingTV`
* `StreamingMovies`
* `Contract`
* `PaperlessBilling`
* `PaymentMethod`
* `MonthlyCharges`
* `TotalCharges`
* `Churn`

### Target Variable

```text
TotalCharges
```

`TotalCharges` is used as the target variable for the regression analysis.

---

## 🛠️ Technologies & Libraries

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Inspection
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Simple Linear Regression
   ↓
Multiple Linear Regression
   ↓
Prediction
   ↓
Regression Evaluation
   ↓
Visualization
   ↓
Result Interpretation
```

---

## 📈 Regression Evaluation

The regression analysis uses standard evaluation metrics, including:

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics help measure the difference between actual and predicted `TotalCharges` and understand the performance of the regression analysis.

---

## 📁 Project Structure

```text
Telco-Customer-Churn-Analysis/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebook/
│   └── Telco_Customer_Churn_Regression.ipynb
│
└── README.md
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Telco-Customer-Churn-Analysis.git
```

### Navigate to the project

```bash
cd Telco-Customer-Churn-Analysis
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open the notebook

```bash
jupyter notebook
```

Then open:

```text
notebook/Telco_Customer_Churn_Regression.ipynb
```

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
pandas
numpy
matplotlib
scikit-learn
jupyter
```

Install the required libraries with:

```bash
pip install -r requirements.txt
```

---

## ⚠️ Dataset Path

When uploading the project to GitHub, avoid using a local Windows path such as:

```python
C:/Users/pradh/OneDrive/Desktop/Study Files/Machine Learning/Telco-Customer-Churn.csv
```

Instead, use a relative project path such as:

```python
df = pd.read_csv("../data/Telco-Customer-Churn.csv")
```

This makes the notebook easier for others to run after cloning the repository.

---

## 💡 Key Learning Outcomes

Through this p
