# HR Employee Attrition Analysis

## 📌 Project Overview

This project presents an end-to-end analysis of employee attrition using Python, statistical analysis, machine learning, and Power BI.

The objective is to identify key factors associated with employee turnover, understand employee attrition patterns, build a predictive classification model, and communicate actionable business insights through an interactive Power BI dashboard.

The analysis is performed on a dataset containing **1,470 employee records**.

## 🎯 Business Objective

Employee attrition can increase recruitment costs, affect productivity, and create workforce instability.

This project aims to answer key business questions such as:

* Which departments experience higher employee attrition?
* How does overtime affect employee turnover?
* Does business travel influence attrition?
* Which job roles have higher attrition rates?
* How does job satisfaction relate to employee turnover?
* Which employee characteristics are associated with higher attrition risk?
* Can machine learning help identify employees who may be at higher risk of leaving?

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Statsmodels**
* **SQL**
* **Power BI**
* **DAX**
* **Jupyter Notebook**

## 🔍 Analytical Workflow

The project follows an end-to-end analytics workflow:

1. Data understanding
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Univariate and bivariate analysis
5. Correlation analysis
6. Feature engineering
7. Multicollinearity analysis using VIF
8. Regression analysis
9. Regression diagnostics
10. Logistic Regression
11. Model evaluation
12. Feature importance analysis
13. Power BI dashboard development
14. Business insights and recommendations

## 📊 Exploratory Data Analysis

The analysis investigates employee attrition across multiple dimensions, including:

* Department
* Business Travel
* Overtime
* Job Role
* Job Satisfaction
* Age
* Years at Company
* Job Level
* Monthly Income
* Employee demographics

## 📈 Key Dashboard Metrics

The Power BI dashboard presents the following key metrics:

| Metric                 |  Value |
| ---------------------- | -----: |
| Total Employees        |  1,470 |
| Employees Who Left     |    237 |
| Overall Attrition Rate | 16.12% |

## 📊 Power BI Dashboard

The interactive Power BI dashboard includes:

* Attrition Rate by Department
* Attrition Rate by Overtime
* Attrition Rate by Business Travel
* Attrition Rate by Job Role
* Attrition Rate by Job Satisfaction
* Attrition Rate by Age Group
* Attrition Rate by Years at Company

### Interactive Filters

The dashboard includes slicers for:

* Department
* Business Travel
* Overtime
* Job Role

The dashboard can be explored interactively by opening the `.pbix` file using Power BI Desktop.

## 🤖 Machine Learning

A **Logistic Regression** model was developed to predict employee attrition.

The machine learning workflow includes:

* Feature preprocessing
* Categorical encoding
* Feature scaling
* Train-test split
* Logistic Regression
* Confusion matrix
* Classification report
* Precision
* Recall
* F1-score
* ROC-AUC
* Feature coefficient analysis

The model achieved an approximate **ROC-AUC of 0.81**.

Because the target variable is imbalanced, model performance was evaluated using multiple classification metrics rather than accuracy alone.

## 📐 Statistical Analysis

The project also includes statistical and regression analysis covering:

* R²
* Adjusted R²
* Multicollinearity
* Variance Inflation Factor (VIF)
* Regression assumptions
* Residual analysis
* Homoscedasticity
* Durbin-Watson statistic

## 💡 Key Business Insights

The analysis identified several notable attrition patterns.

### Overtime

Employees working overtime showed a substantially higher attrition rate than employees who did not work overtime.

* Overtime: **30.53%**
* No Overtime: **10.44%**

### Business Travel

Employees who travelled frequently showed higher attrition compared with employees who travelled rarely or did not travel.

* Travel Frequently: **24.91%**
* Travel Rarely: **14.96%**
* Non-Travel: **8.00%**

### Department

Sales had the highest attrition rate among the three major departments analyzed.

* Sales: **20.63%**
* Human Resources: **19.05%**
* Research & Development: **13.84%**

### Job Satisfaction

Lower job satisfaction was associated with higher observed attrition.

* Satisfaction 1: **22.84%**
* Satisfaction 2: **16.43%**
* Satisfaction 3: **16.52%**
* Satisfaction 4: **11.33%**

### Job Role

Attrition varied considerably across job roles, with some roles showing substantially higher employee turnover than others.

## 💼 Business Recommendations

Based on the analysis, organizations could consider:

* Monitoring excessive overtime and workload.
* Improving work-life balance initiatives.
* Investigating retention challenges in high-attrition departments and job roles.
* Strengthening employee engagement programs.
* Reviewing travel requirements for frequently travelling employees.
* Developing targeted employee retention strategies.
* Using predictive analytics to identify higher-risk employee groups.

These recommendations should be combined with additional organizational and HR context before making employee-level decisions.

## 📁 Repository Structure

```text
HR-Employee-Attrition-Analysis/
│
├── PowerBI/
│   ├── HR Employee Attrition Analysis.pbix
│   └── README.md
│
├── Python/
│   ├── HR_Attrition_Analysis.ipynb
│   └── README.md
│
├── HR ATTRITION DASHBOARD.png
│
└── README.md
```

## 📂 Project Components

### Python Analysis

The `Python` folder contains the complete Jupyter Notebook covering data analysis, visualization, statistical analysis, and machine learning.

### Power BI Dashboard

The `PowerBI` folder contains the interactive Power BI dashboard file.

### Dashboard Preview

The repository also contains a dashboard screenshot for quick visual reference.

## 🚀 How to Use This Project

### Python

Open the following file using Jupyter Notebook or Google Colab:

`Python/HR_Attrition_Analysis.ipynb`

### Power BI

Download and open:

`PowerBI/HR Employee Attrition Analysis.pbix`

using **Power BI Desktop**.

## ⚠️ Data Availability

The original employee-level dataset is not included in this repository.

The repository contains the analytical notebook, Power BI dashboard, dashboard preview, and project documentation.

## 👩‍💻 Author

**Neha Priya**

**Skills:** Python | SQL | Power BI | Machine Learning | Data Analysis
