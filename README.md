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


 
