# Employee Data Preprocessing and Analysis

 # Project Overview

This project focuses on preprocessing and analyzing an Employee dataset using Python. The main objective is to improve the quality, reliability, and usefulness of the data by handling missing values, duplicate records, outliers, inconsistent values, and categorical data.The project also includes data analysis, visualization, data encoding, and feature scaling to prepare the dataset for machine learning applications.
Objectives

# The main objectives of this project are:

- Explore the Employee dataset.
- Identify unique values and their lengths.
- Perform statistical analysis.
- Rename columns for better readability.
- Identify and handle missing or inappropriate values.
- Remove duplicate records.
- Identify outliers.
- Analyze the relationship between age and salary.
- Analyze the number of employees from different places.
- Convert categorical data into numerical form.
- Apply feature scaling using StandardScaler and MinMaxScaler.

# Dataset

The dataset used in this project is an Employee dataset.

# The main features in the dataset include:

- Company
- Age
- Salary
- Place
- Country
- Gender

# Technologies and Libraries Used

The project was implemented using Python.

# Libraries used:

- Pandas – for data loading, manipulation, and analysis
- NumPy – for numerical operations
- Matplotlib – for data visualization
- Scikit-learn – for data encoding and feature scaling

# Data Preprocessing

### 1. Data Exploration

The dataset was explored to understand its structure and contents.

The following tasks were performed:

- Displayed information about the dataset.
- Found unique values in each column.
- Found the number of unique values in each feature.
- Performed statistical analysis using descriptive statistics.
- Renamed the columns for easier use.

---

### 2. Data Cleaning

The dataset was cleaned to improve data quality.

The following preprocessing steps were performed:

- Identified missing values.
- Replaced inappropriate age values of `0` with `NaN`.
- Removed duplicate rows.
- Identified outliers using the IQR method.
- Treated missing numerical values using median values.
- Treated missing categorical values using mode values.

## Data Analysis

Two main analysis tasks were performed.

### Age and Salary Analysis

Employees with:

- Age greater than 40
- Salary less than 5000

were filtered from the dataset.

A scatter plot was created to visualize the relationship between age and salary.

### Employees by Place

The number of employees from each place was calculated using value counts.

A bar chart was created to visually represent the number of employees from each place.

## Data Encoding

Categorical variables were converted into numerical representations so that the data could be used for machine learning.

The following techniques were used:

- Label Encoding
- One-Hot Encoding

Label encoding was used for suitable categorical data, while one-hot encoding was used to represent categorical values as separate numerical columns.


## Feature Scaling

Feature scaling was performed after data encoding.

Two scaling techniques were applied:

### StandardScaler

StandardScaler standardizes numerical features based on their mean and standard deviation.

### MinMaxScaler

MinMaxScaler transforms numerical values into a specified range, generally between 0 and 1.

Both methods were applied to the numerical features such as age and salary

## Visualizations

The project includes the following visualizations:

1. Age vs Salary scatter plot
2. Number of employees from each place bar chart

These visualizations help in understanding patterns and distributions in the dataset.
