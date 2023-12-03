# Diabetes Dataset Analysis

## Overview

Diabetes is a prevalent chronic disease in the United States, impacting millions of Americans each year and posing a significant economic burden. This dataset, sourced from the "diabetes_012_health_indicators_BRFSS2015.csv" file, contains various health indicators related to diabetes and associated factors.

### Columns and Descriptions

- **Diabetes_012:** Indicator for the presence of diabetes (No Diabetes, Pre-Diabetic, Diabetic).
- **HighBP:** Binary indicator for blood pressure (Normal BP, High BP).
- **HighChol:** Binary indicator for cholesterol levels (Normal Cholesterol, High Cholesterol).
- **CholCheck:** Binary indicator for cholesterol check (Not Checked, Checked).
- **BMI:** Body Mass Index (numeric).
- **Smoker:** Binary indicator for smoking status (Non-Smoker, Smoker).
- **Stroke:** Binary indicator for the history of stroke (No Stroke, Stroke).
- **HeartDiseaseorAttack:** Binary indicator for the history of heart disease or heart attack (No Heart Disease/Attack, Heart Disease/Attack).
- **PhysActivity:** Binary indicator for physical activity (Inactive, Active).
- **Fruits:** Numeric indicator for daily fruit consumption (No Fruits/Day, 1 or More Fruits/Day).
- **Veggies:** Numeric indicator for daily vegetable consumption (No Veggies/Day, 1 or More Veggies/Day).
- **HvyAlcoholConsump:** Binary indicator for heavy alcohol consumption (No Alcohol, Alcoholic).
- **AnyHealthcare:** Binary indicator for access to any healthcare (No Healthcare, Have Healthcare).
- **NoDocbcCost:** Binary indicator for no doctor visit due to cost (Cost is not an Issue, No Visit Due to Cost).
- **GenHlth:** Numeric indicator for general health status (Excellent, Very Good, Good, Fair, Poor).
- **MentHlth:** Numeric indicator for mental health status.
- **PhysHlth:** Numeric indicator for physical health status.
- **DiffWalk:** Binary indicator for difficulty in walking (No Difficulty, Yes have Difficulty).
- **Sex:** Binary indicator for gender (Female, Male).
- **Age:** Numeric indicator for age (18-24 Years, 25-29 Years, ..., 80 Years or older).
- **Education:** Numeric indicator for education level (Never attended school..., College 4 years or more).
- **Income:** Numeric indicator for income level (less than $10,000, ..., $75,000 or more).

## Exploratory Data Analysis (EDA)

The analysis includes the following steps:

1. Data Import and Overview
   - Importing the dataset and checking its basic information.

2. Data Description
   - Describing the numeric values of the dataset.

3. Missing Values
   - Analyzing and visualizing missing values in the dataset.

4. Data Distribution
   - Plotting the distribution of each column's data.

5. Correlation Analysis
   - Creating a heatmap to check the correlation between columns.

6. Correlation Thresholds
   - Setting correlation thresholds and plotting highly positive and negative correlations.

7. Target Correlation
   - Analyzing the correlation of the target variable ("Diabetes_012") with other columns.

8. Population Distribution
   - Visualizing the population distribution of the dataset.

9. Diabetes Frequency Analysis
   - Analyzing the frequency of diabetes based on various health indicators.

10. BMI Group Analysis
    - Creating BMI groups and analyzing the diabetes frequency for each group.

11. Statistical Tests
    - Conducting statistical tests (t-test, Pearson correlation, Shapiro-Wilk) to derive insights.

## Conclusion

This readme provides an in-depth analysis of the diabetes dataset, offering valuable insights into the relationships between various health indicators and the presence of diabetes. The visualizations and statistical tests enhance our understanding of the dataset and can inform further research or decision-making processes related to diabetes and associated factors.
