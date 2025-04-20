# Socioeconomic-Factors-and-Income-Dataset
# Socioeconomic Factors and Income Dataset Analysis

## Overview
This Jupyter notebook analyzes a dataset containing socioeconomic factors and income information for individuals. The dataset includes variables such as ID, sex, marital status, age, education, income, occupation, and settlement size.

## Key Questions Explored
1. Which demographic groups (by age, sex, marital status) earn the highest average income?
2. Is there a gender income gap in this dataset?
3. Does marital status affect income levels?

## Analysis Highlights

### 1. Highest Earning Demographic Groups
- **Gender Analysis**: Males earn higher total income than females in this dataset (Male: 138,763,895 vs Female: 103,144,943)
- **Age Analysis**: The 25-34 age group earns the highest total income (92,014,432), followed by 35-44 (62,086,851)
- **Marital Status**: Single individuals have the highest total income among marital status categories

### 2. Gender Income Gap
- Significant income gap exists between genders
- Males earn approximately 35.6 million more in total income than females
- Visualization shows clear disparity in income distribution between sexes

### 3. Marital Status and Income
- Single individuals show the highest total income
- Analysis suggests marital status does affect income levels

## Dataset Structure
The dataset contains the following columns:
- ID: Unique identifier
- Sex: Male/Female
- Marital status: Single/Non-single categories
- Age: Numerical age values
- Education: Education levels (university/high school)
- Income: Numerical income values
- Occupation: Job categories
- Settlement size: Numerical values (0-2 scale)

## Methodology
- Data loaded using pandas
- Visualizations created with matplotlib and seaborn
- Groupby operations for demographic analysis
- Age grouped into brackets for better analysis
- Statistical comparisons between groups

## Key Findings
1. Clear gender disparity in income exists
2. Middle-aged individuals (25-44) earn the most
3. Single individuals have higher total income than non-singles
4. Occupation type correlates with income levels

## How to Use This Notebook
1. Ensure required libraries are installed (pandas, seaborn, matplotlib, numpy)
2. Load the dataset ('sgdata.csv') in the specified path
3. Run cells sequentially to reproduce analysis
4. Modify visualizations or analysis as needed

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- seaborn
- matplotlib
- numpy

## Author
- Etesin Ediomo Usoro
- ediomoetesin40@gmail.com
  
