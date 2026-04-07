# Data Quality Report

## Issues Identified
- Missing values in Age, Cabin, and Embarked
- Categorical variables not suitable for ML
- Fare values not normalized

## Cleaning Steps
- Filled Age with median
- Replaced Cabin with "Unknown"
- Filled Embarked with mode
- Encoded categorical variables
- Normalized Fare

## Improvements
- No missing values remain
- Dataset is machine-learning ready
- Features are standardized and numeric
