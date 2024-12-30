Name:Sunny Patel
Company:CODTECH IT SOLUTIONS
ID:CT08DS394
Domain:Data Science
Durations:December 2024 to Jan 2025

 Project: Exploratory Data Analysis (EDA) on a Supermarket Sales Dataset
This project performs Exploratory Data Analysis (EDA) on a supermarket sales dataset to uncover patterns, correlations, and insights from the data.

Key Steps:
Importing Libraries:

pandas: For data manipulation and handling.
seaborn and matplotlib.pyplot: For data visualization and plotting.
Loading the Dataset:

The dataset is loaded from a ZIP file (database-supermarket-sales-csv.zip).
Exploring the Dataset:

Basic dataset exploration using functions such as:
data.head(): Displays the first few rows of the dataset.
data.shape: Returns the dimensions of the dataset (rows, columns).
data.describe(): Provides summary statistics for numerical columns.
data.info(): Displays data types and non-null counts for each column.
Missing values are handled using forward fill (data.fillna(method='ffill')).
Column Inspection:

The script lists all column names to guide users in selecting which columns to analyze further.
Data Visualization:

Histogram: Displays the distribution of a selected numeric column (default: Total).
Heatmap: Highlights correlations between numeric columns using sns.heatmap.
Boxplot: Identifies outliers and visualizes the spread of a selected numeric column.



Project: Linear Regression on Salary Prediction
This project implements a Linear Regression model to predict Salary based on Years of Experience. The key steps involved are as follows:

Steps:
Import Libraries: Utilizes essential libraries such as pandas, numpy, matplotlib, and scikit-learn for data handling, visualization, and machine learning.
Load Dataset: Loads the dataset from a specified CSV file path with error handling to ensure the file exists.
Data Exploration: Displays basic dataset summaries (head, info, and descriptive statistics) to understand its structure.
Feature Selection: Selects the relevant columns, i.e., YearsExperience as the independent variable and Salary as the dependent variable.
Data Splitting: Splits the dataset into training (80%) and testing (20%) sets using train_test_split for model validation.
Model Training: Trains a Linear Regression model on the training dataset using scikit-learn.
Model Evaluation: Evaluates the model performance using Mean Squared Error (MSE) and R-squared (R²) metrics.
Visualization: Generates a scatter plot of actual data points and overlays the regression line for intuitive visualization.
Outputs:
Evaluation metrics: MSE and R².
A visual plot of the regression line showing the relationship between Years of Experience and Salary.
