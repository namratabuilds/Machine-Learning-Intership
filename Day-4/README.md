# Day 4 – Data Analysis with Pandas

## Overview

On Day 4, I learned how to use the Pandas library for data analysis and manipulation. I worked with Series and DataFrames, imported datasets from CSV files, cleaned missing data, filtered records, and performed basic data analysis.

## Topics Covered

* Pandas Series
* DataFrames
* Data Selection
* Indexing
* CSV File Handling
* Data Cleaning
* Filtering
* Sorting

## Concepts Practiced

### Pandas Series

* Creating Series from lists
* Default and custom indexing
* Accessing elements

### DataFrames

* Creating DataFrames from dictionaries
* Viewing data using `head()` and `tail()`
* Understanding:

  * `shape`
  * `columns`
  * `index`
  * `info()`
  * `describe()`

### Data Selection

* Selecting single columns
* Selecting multiple columns
* Accessing rows using `loc[]`
* Accessing rows using `iloc[]`
* Retrieving individual values

### CSV File Handling

* Reading CSV files using `pd.read_csv()`

### Data Cleaning

* Finding missing values using `isnull()`
* Counting missing values
* Filling missing values using `fillna()`

### Filtering & Sorting

* Filtering data using conditions
* Applying multiple conditions with `&`
* Sorting data using `sort_values()`

## Programs Completed

### 1. Pandas Series Practice

Created Series using default and custom indexes and accessed values using different indexing methods.

### 2. DataFrame Creation

Built DataFrames from Python dictionaries containing student details such as roll number, name, and marks.

### 3. Data Inspection

Explored DataFrames using:

* `head()`
* `tail()`
* `shape`
* `columns`
* `info()`
* `describe()`

### 4. CSV File Analysis

Imported datasets such as student records and employee data using `pd.read_csv()`.

### 5. Data Selection

Selected required rows and columns using `loc[]` and `iloc[]`.

### 6. Data Cleaning

Detected missing values and replaced them using appropriate methods.

### 7. Data Filtering

Filtered records based on conditions such as marks greater than 80 and combined multiple conditions.

### 8. Data Sorting

Sorted datasets in ascending and descending order using `sort_values()`.

## Learning Outcomes

By the end of Day 4, I was able to:

* Work with Pandas Series and DataFrames.
* Import and analyze CSV datasets.
* Select and retrieve specific data from a DataFrame.
* Identify and handle missing values.
* Filter and sort data efficiently.
* Perform basic exploratory data analysis using Pandas.

## Tools Used

* Python
* Pandas
* Jupyter Notebook
* VS Code

## How to Run

1. Open `Day-4.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the notebook cells in sequence.
3. Explore the outputs for data analysis, filtering, and cleaning operations.

---

### Folder Contents

```text
Day-04-Pandas/
│
├── Day-4.ipynb
├── Dataset
└── README.md
```
