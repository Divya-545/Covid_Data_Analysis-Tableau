# Data Visualization in UK Healthcare: Transforming Complex Data into Actionable Insights
Overview:

This project involves analyzing COVID-19 data to gain insights into case trends and evaluate various regression models. The dataset includes information on COVID-19 cases, deaths, vaccinations, and other related metrics over time. The goal is to preprocess the data, analyze correlations, and build predictive models to forecast cumulative cases. Additionally, visualizations are created using Tableau for interactive exploration

Description

Data Loading and Cleaning
Load Dataset: Reads nation.csv into a Pandas DataFrame.
Inspect Data: Displays basic information about the dataset.
Handle Missing Data: Fills missing values with 0 and drops duplicate rows.
Date Processing: Converts the date column to datetime format, computes daily changes, and extracts date-related features (month, week, day of the week, year quarter).

Data Parsing and Feature Engineering
Parse JSON Data: Extracts age group-specific case counts from JSON strings in male_cases and female_cases columns.
Feature Extraction: Creates new columns for male and female cases in different age groups.

Data Visualization
Missing Data Heatmap: Plots a heatmap to visualize missing values.
Correlation Matrix: Displays the correlation matrix of selected columns.
Year Quarter Distribution: Plots histograms and count plots of the year_quarter column.

Data Preparation for Modeling
One-Hot Encoding: Converts categorical columns into numerical values.
Data Splitting: Splits the data into training and testing sets.

Modeling and Evaluation
Model Training: Trains various regression models including Linear Regression, Lasso Regression, Decision Tree, Random Forest, and Gradient Boosting.
Model Evaluation: Calculates and prints RMSE and R² scores for each model, and plots residuals and Q-Q plots for diagnostic purposes.
Model Comparison: Compares the performance of different models using bar plots for RMSE and R² scores.


Tableau Visualization
: Visualizations created in Tableau to explore trends and patterns interactively. The Tableau workbook (Data_visualization.twb) includes:

Open the Data_visualization.twb file in Tableau Desktop or Tableau Public to explore interactive visualizations. You can filter data, drill down into specific metrics, and create custom views.
