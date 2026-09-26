# Day 9 – Model Evaluation & Feature Scaling

## Overview

On Day 9, I learned how to evaluate the performance of machine learning models using different evaluation metrics. I also explored feature scaling techniques to prepare data before training machine learning models.

## Topics Covered

* Model Evaluation
* Accuracy
* Precision
* Recall
* F1 Score
* Feature Scaling
* Min-Max Scaling
* Standardization

## Concepts Practiced

### Model Evaluation Metrics

#### Accuracy

* Measuring the overall performance of a classification model
* Using `accuracy_score()`

#### Precision

* Measuring how many predicted positive values are actually positive
* Using `precision_score()`

#### Recall

* Measuring how many actual positive values are correctly identified
* Using `recall_score()`

#### F1 Score

* Calculating the balance between Precision and Recall
* Using `f1_score()`

### Feature Scaling

#### Min-Max Scaling

* Scaling values between 0 and 1
* Using `MinMaxScaler`

#### Standardization

* Transforming data to have zero mean and unit variance
* Using `StandardScaler`

## Projects Completed

### Model Evaluation Projects

#### 1. Student Result Prediction

Evaluated the performance of a classification model using Accuracy, Precision, Recall, and F1 Score.

#### 2. Weather Prediction

Measured the performance of weather prediction using classification evaluation metrics.

#### 3. Model Performance Analysis

Compared Accuracy, Precision, Recall, and F1 Score to better understand model performance.

---

### Feature Scaling Projects

#### 1. House Price Data Scaling

Applied Min-Max Scaling to normalize house size values before model training.

#### 2. Salary Data Standardization

Used StandardScaler to standardize salary values for machine learning models.

## Learning Outcomes

By the end of Day 9, I was able to:

* Evaluate machine learning models using different performance metrics.
* Understand the importance of Accuracy, Precision, Recall, and F1 Score.
* Apply Min-Max Scaling and Standardization to numerical data.
* Prepare datasets for machine learning using feature scaling techniques.
* Understand why preprocessing is important before training machine learning models.

## Tools & Libraries Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook
* VS Code

## How to Run

1. Open `Day-9.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the notebook cells in sequence.
3. Observe the evaluation metrics and feature scaling outputs.

---

### Folder Contents

```text
Day-09-Model-Evaluation/
│
├── Day-9.ipynb
└── README.md
```
