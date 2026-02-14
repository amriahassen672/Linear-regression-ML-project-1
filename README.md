# Health Insurance Price Prediction Using Linear Regression

[![Python](https://img.shields.io/badge/python-3.x-blue?logo=python)](https://www.python.org/)
[![ML](https://img.shields.io/badge/model-Linear%20Regression-green)]()
[![Status](https://img.shields.io/badge/status-complete-success)]()

This project builds a **machine learning model using Linear Regression** to predict **health insurance prices** based on individual attributes. The focus of the project is on **data analysis, preprocessing, and model interpretation** rather than complex modeling.

---

## Project Overview

Health insurance costs depend on several factors such as age, BMI, smoking habits, and region.  
This project uses **Linear Regression** to model the relationship between these features and insurance charges.

The workflow emphasizes:
- Exploratory Data Analysis (EDA)
- Proper data preprocessing
- Model training and evaluation

---

## Dataset Description

The dataset contains the following features:
- `age` – Age of the individual
- `sex` – Gender
- `bmi` – Body Mass Index
- `children` – Number of dependents
- `smoker` – Smoking status
- `region` – Residential region
- `charges` – Health insurance cost (target variable)

---

## Workflow

### 1. Exploratory Data Analysis (EDA)
- Analyzed feature distributions and relationships
- Visualized correlations between variables
- Identified outliers and trends affecting insurance charges

### 2. Data Preprocessing
- **Imputation:** Handled missing values
- **Encoding:** Converted categorical variables into numerical form
- **Scaling:** Scaled numerical features to improve model performance

### 3. Model Building
- Implemented a **Linear Regression** model
- Split the dataset into training and testing sets
- Trained the model on processed data

### 4. Model Evaluation
- Evaluated performance using:
  - R² score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
- Interpreted coefficients to understand feature impact

---

## Tools & Libraries

- Python 3.x
- pandas, numpy — data manipulation
- matplotlib, seaborn — data visualization
- scikit-learn — preprocessing, Linear Regression, evaluation metrics

---

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>


