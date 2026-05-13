# Iris Dataset Exploration and Visualization

## Project Overview

This project demonstrates how to load, inspect, analyze, and visualize a simple dataset using Python. The dataset used in this project is the famous **Iris Dataset**, which contains flower measurements for three different Iris species.

The main goal of this task is to understand basic data exploration and visualization techniques using:

- pandas
- seaborn
- matplotlib

## Objective

The objective of this project is to learn how to:

- Load a dataset using pandas
- Inspect the structure of the dataset
- View basic information and summary statistics
- Create visualizations to understand relationships and distributions
- Identify possible outliers using box plots

## Dataset

The dataset used is the **Iris Dataset**.

It contains measurements of Iris flowers from three species:

- Setosa
- Versicolor
- Virginica

The dataset includes the following columns:

- sepal_length
- sepal_width
- petal_length
- petal_width
- species

## Technologies Used

- Python
- pandas
- seaborn
- matplotlib

## Project Steps

### 1. Import Libraries

The required Python libraries are imported:

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
2. Load the Dataset

The Iris dataset is loaded using seaborn:
iris = sns.load_dataset("iris")
3. Inspect the Dataset

The dataset is inspected using the following commands:

iris.shape
iris.columns
iris.head()
iris.info()
iris.describe()

These commands help us understand:

Number of rows and columns
Column names
First few records
Data types
Missing values
Summary statistics
4. Visualize the Dataset

Different visualizations are created to better understand the dataset.

Scatter Plot

Scatter plots are used to show relationships between two numerical features.

Examples:

Sepal length vs Sepal width
Petal length vs Petal width
Histograms

Histograms are used to show the distribution of numerical values.

Box Plots

Box plots are used to compare feature values and identify possible outliers.

How to Run the Project
Install the required libraries:
pip install pandas seaborn matplotlib
Run the Python script:
python iris_visualization.py

Or run the code in Jupyter Notebook or Google Colab.

Expected Output

The program will display:

Dataset shape
Column names
First five rows
Dataset information
Summary statistics
Scatter plots
Histograms
Box plots
Learning Outcomes

After completing this project, you will understand how to:

Load a dataset in Python
Explore data using pandas
Generate descriptive statistics
Create basic visualizations using seaborn and matplotlib
Analyze feature relationships and distributions
Conclusion

This project provides a beginner-friendly introduction to data exploration and visualization. The Iris Dataset is simple and useful for practicing basic data analysis skills in Python.
