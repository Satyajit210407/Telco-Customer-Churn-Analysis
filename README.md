# Telco Customer Churn — Machine Learning Analysis

## 📌 Project Overview

This project focuses on **Machine Learning analysis of Telco Customer data** using Python and Scikit-learn.

The notebook applies **Simple Linear Regression** and **Multiple Linear Regression** to analyze the relationship between customer information and **TotalCharges**.

The project is mainly focused on understanding how regression models can be applied to a real-world customer dataset.

---

## 🎯 Objective

The main objective of this project is to:

* Analyze the Telco Customer dataset
* Prepare numerical data for machine learning
* Understand relationships between variables
* Apply Simple Linear Regression
* Apply Multiple Linear Regression
* Generate predictions
* Evaluate regression model performance

> **Note:** The `Churn` column represents a Yes/No classification outcome. In this project, `Churn` is not used as the regression target. The target variable is `TotalCharges`.

---

## 🤖 Machine Learning Models

### 1. Simple Linear Regression

Simple Linear Regression is used to understand the relationship between a single independent variable and `TotalCharges`.

The project analyzes how **customer tenure** relates to total charges.

```text
TotalCharges = β₀ + β₁ × tenure
```

### 2. Multiple Linear Regression

Multiple Linear Regression is used to analyze `TotalCharges` using multiple numerical variables.

```text
TotalCharges = β₀ + β₁X₁ + β₂X₂ + ... + βₙXₙ
```

This provides a broader view of the factors associated with a customer's total charges.

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

---

## 🛠️ Technologies & Libraries

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**

---

## 🔄 Machine Learning Workflow

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
Model Evaluation
   ↓
Visualization
```

---

## 📈 Model Evaluation

The regression models are evaluated using standard regression metrics, including:

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics help measure the prediction performance of the regression models.

---

## 📁 Project Structure

```text
Telco-Customer-Churn-Analysis/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Telco_Customer_Churn_Regression.ipynb
│
├── README.md
│
└── requirements.txt
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
notebooks/Telco_Customer_Churn_Regression.ipynb
```

---

## 📦 Requirements

Create a `requirements.txt` file:

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

Through this project, I gained practical experience in:

* Preparing data for Machine Learning
* Working with numerical features
* Understanding linear relationships
* Implementing Simple Linear Regression
* Implementing Multiple Linear Regression
* Making predictions using trained models
* Evaluating regression models
* Visualizing machine learning results
* Using Scikit-learn for model development

---

## 🔮 Future Improvements

Possible future improvements include:

* Developing a **Churn Classification** model
* Applying Logistic Regression
* Testing Decision Trees and Random Forest
* Comparing multiple ML algorithms
* Feature engineering
* Hyperparameter tuning
* Cross-validation
* Model performance comparison

---

## 👨‍💻 Author

**Satyajit Pradhan**

B.Tech — Computer Science & Engineering

Interested in **Data Analytics, Machine Learning, SQL, and Business Intelligence**.

---

## ⭐ Project

If you find this project useful, feel free to explore the notebook and use it as a reference for learning Machine Learning and Regression.

