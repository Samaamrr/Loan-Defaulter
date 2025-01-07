# Credit Default Prediction

## Overview
This project aims to analyze and predict the likelihood of credit defaults based on customer data. The dataset includes information related to loans, customer demographics, employment, and other attributes.

## Features
- **Application Data**: Contains data on loan applications such as the loan amount, income, gender, family status, etc.
- **Previous Application Data**: Historical loan data detailing previous loans, purposes, application statuses, etc.
- **Target Variable**: Indicates whether a customer defaulted (1) or not (0) on the loan.

## Steps in the Project

### 1. Data Import and Basic Exploration
- Libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn` are used for data manipulation and visualization.
- Data is loaded from `application_data.csv` and `previous_application.csv`.

### 2. Data Cleaning and Preprocessing
- Handle missing data by imputing or removing missing values.
- Process categorical variables and encode them appropriately.
- Remove or modify outliers to ensure data quality.
- Feature engineering to create new relevant features.

### 3. Data Analysis and Visualization
- Exploratory data analysis (EDA) is conducted to understand distributions, correlations, and trends.
- Visualizations like histograms, boxplots, and correlation matrices are used to gain insights from the data.

### 4. Feature Selection
- Unnecessary or redundant features are removed.
- Features are selected based on correlation with the target variable and predictive power.


## Recommendations
- Target customers with lower incomes, homeowners, married individuals, and those with higher education levels.
- Avoid offering loans to customers in high-risk occupations or organizations.
- Prioritize applications that have a history of approved loans with fewer cancellations or refusals.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn

## License
This project is licensed under the MIT License - see the LICENSE file for details.
