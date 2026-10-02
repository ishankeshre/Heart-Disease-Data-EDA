
# Pulse of Prevention – Heart Disease Data EDA

## Overview
This project explores heart health data to understand how patient characteristics and clinical measurements vary between individuals with and without heart disease. Using Python, the analysis identifies patterns, correlations, and relationships within the dataset.

## Requirements
- Python 3.x
- Jupyter Notebook

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preparation
- Removed duplicate records, reducing the dataset from 1,025 rows to 302 unique records.
- Checked for missing values.
- Retained 14 columns, including patient measurements and the target variable.
- Prepared the data for statistical analysis and visualization.

## Analysis
The analysis focused on:
- Patient age and gender distribution.
- Resting blood pressure and cholesterol levels.
- Chest pain types and fasting blood sugar.
- Maximum heart rate and exercise-induced angina.
- ECG results, major vessels, and thalassemia.
- Correlations between clinical measurements and heart disease.
- Comparisons between patients with and without heart disease.

## Key Insights
- The cleaned dataset contains 302 records, including 164 with heart disease and 138 without.
- The average patient age is 54.42 years.
- Average resting blood pressure is 131.60, while average cholesterol is 246.50.
- Chest pain type, maximum heart rate, and exercise-induced angina show notable correlations with the target variable.
- The analysis highlights associations in the dataset, not proof of causation.

## Challenges
- Identifying and removing repeated patient records.
- Working with a dataset containing a limited number of unique observations.
- Interpreting correlations without assuming causation.
- The dataset represents a single snapshot and does not support survival or follow-up trend analysis.

## Recommendations
- Use the observed patterns as a starting point for further investigation rather than as a diagnostic tool.
- Validate findings using larger, independent datasets.
- Future analysis could include predictive modeling and statistical testing with appropriate evaluation.

## Conclusion
This project demonstrates how exploratory data analysis can be used to examine health-related data, identify patterns, and understand relationships between clinical measurements. It also highlights the importance of data quality and recognizing the limitations of a dataset.
