# Python — HR Employee Attrition Analysis

## 📌 Overview

This folder contains the Python-based analysis performed as part of the **HR Employee Attrition Analysis** project.

The Jupyter Notebook covers the complete analytical workflow, from data preparation and exploratory analysis to statistical analysis and machine learning.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Statsmodels
* Jupyter Notebook

## 🔍 Analysis Workflow

The notebook includes:

### 1. Data Preparation

* Dataset inspection
* Data cleaning
* Missing-value handling
* Data type validation
* Feature preparation

### 2. Exploratory Data Analysis

The analysis examines:

* Attrition distribution
* Numerical variables
* Categorical variables
* Department-level attrition
* Overtime
* Business Travel
* Job Role
* Job Satisfaction
* Age
* Years at Company
* Employee characteristics

### 3. Correlation Analysis

Correlation analysis is used to understand relationships between numerical variables and identify variables associated with employee attrition.

### 4. Feature Engineering

Relevant features are prepared and transformed for statistical and machine learning models.

### 5. Multicollinearity Analysis

Variance Inflation Factor (**VIF**) is used to identify potential multicollinearity among explanatory variables.

### 6. Regression Analysis

The project explores regression concepts including:

* R²
* Adjusted R²
* Residual analysis
* Regression assumptions
* Homoscedasticity
* Durbin-Watson statistic

### 7. Classification Model

A **Logistic Regression** model is developed to predict employee attrition.

The workflow includes:

* Train-test split
* Categorical encoding
* Feature scaling
* Model training
* Prediction
* Model evaluation
* Feature coefficient analysis

## 📊 Model Evaluation

The classification model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC-AUC

The model achieved an approximate **ROC-AUC of 0.81**.

## 💡 Analytical Objective

The Python analysis aims to identify employee characteristics and workplace factors associated with attrition and provide a foundation for the interactive Power BI reporting layer.

## 📁 Notebook

The main analysis file is:

`HR_Attrition_Analysis.ipynb`

## ▶️ How to Run

The notebook can be opened using:

* Jupyter Notebook
* JupyterLab
* Google Colab

The required Python libraries should be installed before executing the notebook.

## 🎯 Outcome

The Python analysis provides the statistical and machine learning foundation for the overall HR Employee Attrition Analysis project, while the Power BI dashboard presents the findings in an interactive business intelligence format.
