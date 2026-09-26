# Day 10 – Student Performance Prediction (Capstone Project)

## Overview

On the final day of the training program, I developed an end-to-end Machine Learning project to predict whether a student is likely to **Pass** or **Fail** based on their academic performance. This project combines data preprocessing, feature scaling, model training, evaluation, visualization, and real-time prediction using a K-Nearest Neighbors (KNN) classifier.

## Project Objective

The objective of this project is to build a machine learning model that predicts student performance using the following factors:

* Study Hours
* Attendance
* Previous Marks

## Machine Learning Workflow

The project follows a complete machine learning pipeline:

1. Load the dataset
2. Handle missing values
3. Select features and target variable
4. Apply feature scaling using `StandardScaler`
5. Split the dataset into training and testing sets
6. Train the K-Nearest Neighbors (KNN) model
7. Evaluate the model
8. Visualize the data
9. Predict results using user input

## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* VS Code

## Dataset Features

| Feature        | Description                             |
| -------------- | --------------------------------------- |
| Study_Hours    | Number of hours spent studying          |
| Attendance     | Student attendance percentage           |
| Previous_Marks | Marks obtained in previous examinations |
| Pass           | Target variable (1 = Pass, 0 = Fail)    |

## Project Features

* Data preprocessing
* Missing value handling
* Feature scaling using `StandardScaler`
* K-Nearest Neighbors (KNN) Classification
* Train-test split
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
* Data visualization using Matplotlib
* Real-time prediction using user input

## Learning Outcomes

By completing this project, I was able to:

* Build a complete machine learning pipeline.
* Prepare data for machine learning using preprocessing techniques.
* Train and test a KNN classification model.
* Evaluate model performance using multiple evaluation metrics.
* Visualize data using Matplotlib.
* Make predictions using real-time user input.

## How to Run

1. Place `student.csv` in the project folder.
2. Open `Day-10.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the notebook cells in sequence.
4. Enter the required values when prompted to predict whether a student will pass or fail.

---

### Folder Contents

```text
Day-10-Capstone-Project/
│
├── Day-10.ipynb
├── student.csv
├── README.md
```

