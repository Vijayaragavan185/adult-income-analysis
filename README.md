# Adult Income Data Analysis

## Overview
This project performs data cleaning and exploratory data analysis on the Adult Income dataset from the 1994 US Census.

## Dataset
The dataset contains demographic and employment information about individuals, with the target variable indicating whether a person earns more than $50K per year.

## Cleaning Steps
1. Loaded the dataset and assigned appropriate column names
2. Handled missing values in 'workclass', 'occupation', and 'native-country' using mode imputation
3. Removed duplicates
4. Converted categorical variables to proper category data types
5. Standardized the 'income' column format

## EDA Highlights
1. Analyzed distributions of age, education, work hours, etc.
2. Examined relationships between income and various factors
3. Created visualizations showing income disparities across different demographics
4. Performed correlation analysis of numeric features

## Feature Engineering
1. Created age groups for better demographic analysis
2. Categorized work hours into meaningful groups (part-time, full-time, etc.)

## Key Findings
1. Higher education levels strongly correlate with higher income
2. Income disparity exists across different demographic groups
3. Working more hours per week is associated with higher income
4. [Add more insights from your analysis]

## Files
- `adult_income_eda.ipynb`: Jupyter notebook containing all code and analysis
- `adult_cleaned.csv`: Cleaned dataset ready for further analysis or modeling
