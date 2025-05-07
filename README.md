# Data Exploration and Outlier Detection in QVI Transaction Dataset

## Overview
This Python script performs exploratory data analysis (EDA) on a retail sales dataset from QVI. It provides insights into data summarization, missing value detection, outlier identification, and data type checks. The analysis focuses on understanding the distribution of total sales and identifying any outliers in the dataset for further processing.

## Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization (boxplots and histograms).
- **Seaborn**: For statistical visualizations (KDE plots and boxplots).

## How It Works

1. The dataset is loaded from an Excel file using Pandas.
2. Basic summary statistics and missing values are checked with the `describe()` and `isnull().sum()` methods.
3. Outliers in the `TOT_SALES` column are detected using visualizations like boxplots and KDE plots.
4. Numeric columns are selected to focus on relevant data for further analysis.
5. Outliers are removed from the `TOT_SALES` column, followed by plotting the cleaned data to verify the removal.
6. The script checks the data types of each column to ensure proper data formatting for analysis.

## Results
- Summary statistics are displayed, including measures like mean, standard deviation, and percentiles.
- Missing values are identified for further handling.
- Outliers in sales data are identified and removed, improving data quality for further analysis.

## How to Run

1. **Install Dependencies**:
   Ensure the following Python libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
