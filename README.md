# Loan-Defaulter
Bank loan defaulter 

# EDA in a Real Business Scenario: Risk Analytics in Banking and Financial Services

## Overview

This project focuses on applying Exploratory Data Analysis (EDA) techniques to a real-world business scenario, specifically in the banking and financial services domain. The case study aims to provide an understanding of how data can be leveraged to minimize risks, especially related to lending to customers. By performing EDA and other data preprocessing techniques, the goal is to uncover insights that can help improve decision-making processes in financial institutions, particularly in identifying and mitigating the risk of default.

### Key Dataset Details:
- **Target Variable**: 
  - `0`: Non-Defaulter
  - `1`: Defaulter
- **Objective**: Predict whether a customer will default or not on a loan based on various features.

## Steps Involved:

### 1. **Data Import and Basic Exploration**
   - Load the dataset into the environment.
   - Perform an initial exploration to understand the structure, types of data, and summary statistics.
   - Visualize key aspects of the data for further insights.

### 2. **Feature Selection**
   - Identify and select the most relevant features that contribute to predicting the target variable.
   - Eliminate irrelevant or redundant features to improve model performance and reduce complexity.

### 3. **Feature Engineering**
   - Transform existing features into new ones that can better capture patterns in the data.
   - Create new features based on domain knowledge, such as customer age categories, income brackets, etc.

### 4. **Missing Value Imputation**
   - Address any missing or incomplete data by employing suitable imputation techniques.
   - Replace missing values using methods like mean, median, or more advanced approaches like KNN imputation.

### 5. **Value Modification**
   - Normalize or scale numerical values to bring all features to a comparable range.
   - Modify or encode categorical variables to make them suitable for analysis.

### 6. **Outlier Detection and Treatment**
   - Identify outliers that may significantly distort analysis.
   - Use techniques like Z-score or IQR-based methods to detect and treat outliers.

### 7. **Binning**
   - Group continuous features into discrete categories or bins (e.g., low, medium, high income).
   - This helps in simplifying the data and enhancing model interpretability.

### 8. **Data Analysis**
   - Perform thorough statistical analysis and visualizations to understand relationships between features.
   - Examine correlations between features and the target variable, and assess feature importance.

### 9. **Explore Previous Dataset**
   - If applicable, analyze an older version or a related dataset to see any patterns or insights that can be applied to the current case study.

### 10. **Merge App and Previous Dataset**
   - Integrate relevant data from multiple sources to form a comprehensive dataset for analysis.
   - Clean and harmonize the combined data for further analysis.

## Conclusion / Insights:
By the end of this project, we aim to:
- Understand the key factors influencing loan defaults.
- Discover actionable insights to reduce financial risk when lending to customers.
- Lay the foundation for building predictive models for loan default risk in the banking and financial sectors.

## Project Structure:
- `data/`: Contains all input datasets.
- `notebooks/`: Jupyter notebooks for EDA and data preprocessing.
- `scripts/`: Python scripts used for data manipulation, feature engineering, etc.
- `output/`: Folder for visualizations, analysis results, and other output files.

## Dependencies:
This project uses the following Python libraries:
- `pandas`: Data manipulation and analysis.
- `numpy`: Numerical computing.
- `matplotlib`, `seaborn`: Data visualization.
- `scikit-learn`: Machine learning and data preprocessing.
- `statsmodels`: Statistical analysis.

## Dataset:
- This project has 3 files :
- application.csv
- previous_application.csv
- columns_description.csv
