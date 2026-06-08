# Employee Performance Predictor

## Project Overview

The Employee Performance Predictor is a Machine Learning project designed to analyze employee-related factors and predict employee performance levels (High, Medium, or Low).

This project helps organizations identify high-performing employees, understand key performance drivers, and support HR decision-making through predictive analytics.

---

## Business Problem

Human Resource departments often need data-driven methods to evaluate employee performance.

This project uses employee information such as:

- Age
- Experience
- Department
- Salary
- Training Hours
- Attendance
- Projects Completed
- Performance Score

to predict employee performance categories.

---

## Objectives

- Analyze employee data
- Perform exploratory data analysis (EDA)
- Build a machine learning classification model
- Predict employee performance levels
- Visualize important employee performance factors

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Google Colab

---

## Machine Learning Model

### Algorithm Used

- Random Forest Classifier

### Workflow

1. Data Generation
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Employee Performance Prediction
10. Model Deployment Preparation

---

## Project Structure

Employee-Performance-Predictor/

├── data/
│ └── employee_data.csv

├── notebooks/
│ └── Employee_Performance_Predictor.ipynb

├── models/
│ └── employee_performance_model.pkl

├── outputs/
│ └── employee_prediction.csv

├── images/
│ ├── performance_distribution.png
│ ├── department_distribution.png
│ ├── salary_distribution.png
│ ├── correlation_heatmap.png
│ ├── confusion_matrix.png
│ └── feature_importance.png

├── requirements.txt

└── README.md

---

## Exploratory Data Analysis

The project includes:

- Employee Performance Distribution
- Department Distribution Analysis
- Salary Distribution Analysis
- Correlation Heatmap
- Confusion Matrix Visualization
- Feature Importance Analysis

---

## Key Insights

- Performance Score was the strongest predictor of employee performance.
- Training Hours positively influenced employee outcomes.
- Attendance and Project Completion contributed to performance classification.
- Department had the lowest impact among available features.

---

## Results

The Random Forest model successfully classified employee performance levels and generated predictions for new employee records.

The model was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Author

**Mahek Shaikh**

