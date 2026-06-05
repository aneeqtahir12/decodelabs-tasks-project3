# Data Science Project 3 - Decodelabs Tasks

This repository contains my third Data Science project completed as part of the Decodelabs internship tasks.

## Project Overview

This project focuses on data analysis, visualization, and basic machine learning using Python. It includes data preprocessing, exploratory data analysis, data visualization, and applying a classification model to predict outcomes.

## Tasks Completed

### Task 1: Data Loading and Understanding

* Loaded dataset using Pandas (`read_csv`)
* Viewed dataset using `head()`
* Checked dataset structure using `info()`, `shape`, and `size`
* Generated statistical summary using `describe()`

### Task 2: Data Cleaning

* Checked missing values using `isnull().sum()`
* Identified duplicate records using `duplicated()`
* Removed duplicate data using `drop_duplicates()`
* Prepared clean dataset for further analysis

### Task 3: Data Analysis

* Analyzed target variable using `value_counts(normalize=True)`
* Calculated mean values using `groupby()`
* Explored relationships between Age, Salary, and Purchase behavior

### Task 4: Data Visualization

* Created scatter plot to visualize relationship between Age and Estimated Salary
* Used color differentiation based on purchase status
* Created count plot to show distribution of target variable
* Used Matplotlib and Seaborn for visualization

### Task 5: Machine Learning Model

* Split dataset into training and testing sets using `train_test_split`
* Applied feature scaling using `StandardScaler`
* Trained Logistic Regression model
* Made predictions on test data
* Evaluated model using:

  * Accuracy Score
  * Confusion Matrix
  * Classification Report

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset Description

The dataset contains information about users such as Age and Estimated Salary, along with a target variable indicating whether a product was purchased or not.

## Key Learnings

* Data preprocessing and cleaning
* Exploratory data analysis techniques
* Data visualization using graphs
* Understanding classification problems
* Applying Logistic Regression model
* Model evaluation techniques

## Project Files

* Project 3.ipynb (Main notebook file)

## Author

Muhammad Aneeq Tahir

## Submission

This project is submitted as part of the Decodelabs internship tasks.

## Future Improvements

* Try different machine learning models
* Improve model accuracy with tuning
* Add more visualizations
* Perform feature engineering
