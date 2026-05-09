# Codec_projects-
internship projects from codec
# Employee Attrition Analysis and Prediction System

## Project Overview

The Employee Attrition Analysis and Prediction System is a machine learning project developed to analyze employee data and predict whether an employee is likely to leave the organization. The project helps organizations identify important factors contributing to attrition and supports data-driven HR decision-making.

This system uses classification algorithms and data analysis techniques to detect attrition patterns from HR datasets.

---

## Objectives

- Analyze employee-related factors affecting attrition
- Perform exploratory data analysis (EDA)
- Build a machine learning model for attrition prediction
- Evaluate model performance using classification metrics
- Save and reuse the trained prediction model

---

## Dataset

The project uses the IBM HR Analytics Employee Attrition dataset.

### Dataset Features
- Age
- Department
- Education
- Job Role
- Monthly Income
- Job Satisfaction
- Work-Life Balance
- Years at Company
- Attrition Status

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection
The HR employee attrition dataset is loaded using Pandas.

### 2. Data Preprocessing
- Handling categorical values
- Encoding labels
- Feature preparation
- Data cleaning

### 3. Exploratory Data Analysis
Visualization and statistical analysis are performed to identify:
- Attrition distribution
- Salary patterns
- Department-wise attrition
- Age and experience analysis

### 4. Model Training
Machine learning classification models are trained using:
- Logistic Regression

### 5. Model Evaluation
The model is evaluated using:
- Accuracy Score
- Classification Report
- Precision
- Recall
- F1-Score

### 6. Model Saving
The trained model is saved using Joblib for future predictions.

---

## Project Structure

```text
Employee-Attrition-Project/
│
├── codec_attrition.ipynb
├── attrition_model.pkl
├── README.md
├── LICENSE
└── WA_Fn-UseC_-HR-Employee-Attrition.csv
