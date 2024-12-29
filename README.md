Name:Sunny Patel
Company:CODTECH IT SOLUTIONS
ID:CT08DS394
Domain:Data Science
Durations:December 2024 to Jan 2025

Project: Exploratory Data Analysis (EDA) on a supermarket sales dataset.

Key Steps:
Importing Libraries:
pandas for data manipulation.
seaborn and matplotlib.pyplot for data visualization.

Loading the Dataset:
The dataset is loaded from a ZIP file (database-supermarket-sales-csv.zip).
Exploring the Dataset:
data.head(), data.shape, data.describe(), and data.info() give an overview of the data structure, size, and basic statistics.
Missing values are checked and handled using forward fill (data.fillna(method='ffill')).

Column Inspection:
The script lists all column names to help the user decide which columns to analyze.

Data Visualization:
Histogram: Displays the distribution of a selected numeric column (default: Total).
Heatmap: Highlights correlations between numeric columns using sns.heatmap.
Boxplot: Identifies outliers and the spread of the selected numeric column.
