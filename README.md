# Classification of bank clients - churn forecasting
EDA, ML predictive models to identify bank's customers churn
Data source: https://www.kaggle.com/datasets/aakash50897/churn-modellingcsv/data
## Problem Statement
Beta-Bank has been experiencing a steady decline in its client base. While the monthly churn rate is not drastic, it is significant enough to warrant action. Market analysis indicates that retaining existing clients is more cost-effective than acquiring new ones.

To address this issue, I will develop a predictive model to identify clients at risk of leaving the bank in the near future. I will leverage historical data on client behavior and contract terminations, applying exploratory data analysis (EDA) to uncover key patterns and trends. Using machine learning techniques, I will build and evaluate classification models to accurately predict churn, providing actionable insights to help the bank enhance client retention strategies.

### Data Description

Features:
- RowNumber – row index in data
- CustomerId – unique customer identifier
- Surname – last name
- CreditScore – credit rating
- Geography – country of residence
- Gender – gender
- Age – age
- Tenure – amount of real estate owned by the customer
- Balance – account balance
- NumOfProducts – number of bank products used by the customer
- HasCrCard – availability of a credit card
- IsActiveMember – customer activity
- EstimatedSalary – estimated salary

Target (required) feature:
- Exited – fact of customer leaving

## Stages of problem solving
- import libraries
- data lodaing
- exploratory data analysis, EDA
- preprocessing
- models fitting
- prediction

## Exploratory Data Analysis (EDA)

To gain insights into the dataset and prepare it for modeling, I will conduct a thorough exploratory data analysis (EDA). This process will include:
- Assessing the dataset size by determining the number of observations and features.
- Identifying data types for each feature to understand the nature of the variables.
- Defining the target variable and clarifying the type of problem (classification or regression).
- Checking for missing values across different columns and evaluating their impact.
- Analyzing the distribution of feature values, detecting outliers, and identifying anomalies.
- Examining feature relationships, including correlation analysis and their influence on the target variable.
- For classification problems, determining the number of classes and checking if they are balanced.

I will utilize both numerical and visual methods to present the results, incorporating:
- Numerical/Tabular Analysis: Summary statistics, correlation matrices, and feature importance scores.
- Visual Analysis: Histograms, box plots, scatter plots, and heatmaps to reveal trends and dependencies.

Depending on the complexity of the dataset, I will conduct:
- Univariate Analysis – Examining individual feature distributions.
- Bivariate Analysis – Investigating relationships between pairs of features.
- Multivariate Analysis – Analyzing interactions between multiple features simultaneously. 

This structured approach will help identify key patterns in the data, detect potential data quality issues, and ensure optimal feature selection for model training.

## Data preprocessing

Preprocessing Strategy for Model Preparation

To ensure the dataset is clean, consistent, and optimized for machine learning models, I will perform the following preprocessing steps:
- Data Type Conversion: Transform categorical features into dummy (one-hot encoded) binary variables for compatibility with machine learning algorithms.
- Outlier Removal: Identify and handle anomalous data points that could negatively impact model performance.
- Handling Missing Values: Fill missing values in the dataset using appropriate imputation techniques (e.g., mean, median, mode, or predictive methods).
- Feature Scaling: Normalize numerical features to ensure all variables contribute equally to the model and improve convergence speed.
- Feature Engineering: Optimize the dataset for training by selecting relevant features, excluding redundant ones, and merging engineered features when necessary.