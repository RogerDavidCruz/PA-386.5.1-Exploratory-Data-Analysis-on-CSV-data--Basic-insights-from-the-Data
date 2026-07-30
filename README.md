# PA 386.5.1 – Exploratory Data Analysis (EDA) on CSV Data: Basic Insights

## Overview

This practice activity demonstrates how to load CSV data into a Pandas DataFrame, perform basic exploratory data analysis (EDA), and create a line chart using Matplotlib. The lab focuses on understanding the dataset's structure, identifying missing values, and visualizing the relationship between employee age and salary.

## Objectives

* Read CSV files using Pandas
* Explore and summarize a dataset
* Inspect data structure and missing values
* Visualize data using a line chart
* Interpret basic relationships between variables

## Technologies Used

* Python 3
* Pandas
* Matplotlib
* Google Colab / Jupyter Notebook

## Methods & Concepts

* `pd.read_csv()` – Load CSV files into a DataFrame
* `df.head()` – View the first rows of the dataset
* `df.tail()` – View the last rows
* `df.info()` – Inspect data types and missing values
* `df.shape` – Display dataset dimensions
* `df.sort_values()` – Sort data before visualization
* `plt.plot()` – Create a line chart
* `plt.grid()` – Improve chart readability
* `plt.figure()` – Customize figure size
* `plt.show()` – Display the visualization

## Key Points

* CSV files can be efficiently loaded using `pd.read_csv()`.
* EDA begins by examining the dataset's structure, dimensions, and data quality.
* `head()`, `tail()`, `info()`, and `shape` provide quick insights into the dataset.
* Sorting data before plotting can improve the readability of line charts.
* Line graphs are useful for visualizing trends and relationships between numerical variables such as Age and Salary.

## Topics Covered

* Reading CSV files
* Exploratory Data Analysis (EDA)
* Data inspection
* Missing value identification
* Dataset dimensions
* Data visualization
* Line charts
* Employee salary analysis

## Dataset

The lab uses a sample **Employee** dataset containing:

* Name
* Age
* Weight
* Salary

## Learning Outcome

By completing this practice activity, I gained hands-on experience loading CSV files with Pandas, performing basic exploratory data analysis, identifying missing data, and creating Matplotlib line charts to visualize relationships between variables.
