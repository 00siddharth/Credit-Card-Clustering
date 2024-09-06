# Credit Card Clustering and Visualization
## Overview
This project involves clustering credit card data using KMeans and visualizing the results in a 3D scatter plot. The dataset contains features related to customer balances, purchases, and credit limits. The clustering groups customers into different segments based on these features.

## Prerequisites
To run this code, you need to have the following Python packages installed:<br />
'pandas'<br />
'NumPy'<br />
'sci-kit-learn'<br />
'plotly'

## Data
The dataset used is CC GENERAL.csv, which should be placed in the Downloads directory or the appropriate path specified in the script.

## Code Explanation

### 1. Data Loading and Cleaning:
-Load the dataset and drop rows with missing values.

### 2. Feature Selection and Scaling:
-Select relevant features: BALANCE, PURCHASES, CREDIT_LIMIT.<br />
-Apply MinMaxScaler to scale these features between 0 and 1.

### 3. Clustering:
-Use KMeans clustering to group the data into 5 clusters.<br />
-Add cluster labels to the original DataFrame and map these labels to descriptive names.

### 4. Visualization:
-Create a 3D scatter plot using Plotly to visualize the clusters.<br />
-Configure plot appearance and hover information for better insights.
