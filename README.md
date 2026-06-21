# Salary Prediction Using Machine Learning

## Overview

This project builds a Machine Learning model to predict employee salaries based on demographic, educational, and professional attributes. The workflow covers data cleaning, exploratory data analysis (EDA), preprocessing, model training, evaluation, and prediction.

The goal is to demonstrate an end to end Machine Learning pipeline using Python and Scikit-learn.

---

## Dataset

The dataset contains information about employees, including:

* Age
* Gender
* Education Level
* Job Title
* Years of Experience
* Salary (Target Variable)

---

## Project Workflow

### 1. Data Loading

* Load dataset using Pandas
* Explore dataset structure

### 2. Data Cleaning

* Handle missing values
* Check for duplicate records
* Validate data types

### 3. Exploratory Data Analysis (EDA)

* Salary distribution
* Gender distribution
* Education level analysis
* Salary vs Experience analysis
* Correlation analysis
* Job title analysis

### 4. Data Preprocessing

* Missing value imputation
* One Hot Encoding for categorical features
* Train Test Split
* Scikit-learn Pipelines

### 5. Model Training

* Linear Regression
* Random Forest Regressor

### 6. Model Evaluation

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

### 7. Feature Importance

* Identify the most influential features affecting salary predictions

### 8. Salary Prediction

* Predict salary for new employee records

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

salary-prediction-ml/

├── data/

│   └── Salary Data.csv

├── notebooks/

│   └── Salary_Prediction_Workflow.ipynb

├── images/

├── README.md

├── requirements.txt

└── .gitignore

---

## Results

The models were evaluated using multiple regression metrics. Random Forest achieved better predictive performance compared to Linear Regression and was selected as the final model.

---

## Key Insights

* Years of Experience is the strongest predictor of salary.
* Higher education levels generally lead to higher salaries.
* Job title significantly impacts salary predictions.
* Proper preprocessing improves model performance.

---

## Future Improvements

* Hyperparameter Tuning
* Cross Validation
* XGBoost Implementation
* Model Deployment with Streamlit
* Automated Model Tracking

---

## Author

Hamza Ali Malik

BS Computer Science

Aspiring Data Scientist & Machine Learning Engineer

LinkedIn: [Hamza Malik](https://www.linkedin.com/in/hamza-malik-a950192a7)

GitHub: [@hazmaali9708](https://github.com/hazmaali9708)
