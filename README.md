# Red Wine Quality Exploratory Data Analysis (EDA)

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Red Wine Quality dataset obtained from the UCI Machine Learning Repository. The dataset contains physicochemical measurements of red wine samples from Portugal, along with quality ratings assigned through sensory evaluation.

The goal of this project is to explore the dataset, identify patterns and relationships among variables, and investigate which physicochemical properties are associated with wine quality.

## Dataset Source

- **Source:** [UCI Machine Learning Repository — Wine Quality Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv)
- **Dataset:** Red Wine Quality
- **File Format:** CSV
- **Number of Observations:** 1,599
- **Number of Columns:** 12, including the target variable `quality`

The dataset contains 11 physicochemical input features and one output variable representing wine quality.

## Data Preparation and Analysis

The analysis included:

- Examining the dataset structure.

- Generating descriptive statistics.

- Checking for missing values.

- Identifying and removing duplicate records.

- Calculating correlations between variables.

- Creating visualizations to identify patterns and relationships.
## Tools and Libraries

- **Python** — Programming and data analysis.
- **Google Colab** — Cloud-based environment for writing and executing Python code.
<img width="2876" height="911" alt="Image" src="https://github.com/user-attachments/assets/6b4571e2-7ff4-48f0-a717-8a3b7eeb7c2e" />

- **Pandas** — Data manipulation and analysis.
- **NumPy** — Numerical computations.
- **Matplotlib** — Data visualization.
- **Seaborn** — Statistical data visualization.

## Exploratory Data Analysis

The analysis covers the following stages:

1. **Data Loading and Initial Inspection:** Loading the dataset and examining its structure.
2. **Data Cleaning and Validation:** Checking for missing values, duplicate records, and potential data quality issues.
3. **Descriptive Statistical Analysis:** Examining summary statistics to understand the numerical features.
4. **Univariate Analysis:** Exploring individual variable distributions using histograms and other plots.
5. **Bivariate Analysis:** Investigating relationships between physicochemical properties and wine quality.
6. **Correlation Analysis:** Using a correlation matrix and heatmap to examine relationships among numerical variables.
7. **Insight Generation:** Interpreting visualizations and summarizing important patterns discovered during the analysis.

## Dataset Features

The dataset includes the following variables:

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality`

The `quality` variable represents the wine quality score and serves as the primary variable of interest in this analysis.

## Key Findings

- Wine quality ratings of 5 and 6 were the most common.
- Alcohol content had a positive correlation with wine quality (approximately 0.48).
- Volatile acidity had a negative correlation with wine quality (approximately -0.40).
- Fixed acidity was positively correlated with citric acid.
- The dataset showed an imbalanced distribution of quality 

## Visualizations

The notebook includes visualizations such as:

- Wine quality distribution.
<img width="1436" height="923" alt="Image" src="https://github.com/user-attachments/assets/4bc6cbca-a68d-40c7-a307-1b1f17fe5fea" />

- Scatter plot of alcohol content and sulphates by wine quality.
<img width="1385" height="941" alt="Image" src="https://github.com/user-attachments/assets/2d2504b9-c327-4fa4-bd35-dd19d4bae352" />

- Relationships between alcohol content and wine quality.
<img width="1681" height="1046" alt="Image" src="https://github.com/user-attachments/assets/f458627e-1269-4756-bc81-67d3f8beb56a" />

- Relationships between other physicochemical properties.
<img width="2123" height="1309" alt="Image" src="https://github.com/user-attachments/assets/c4906e45-914e-4b1e-98a5-9267982e68e6" />

## Conclusion

The analysis identified relationships between selected chemical properties and wine quality ratings. Alcohol content and volatile acidity showed notable correlations with quality.

These findings describe associations in the dataset and do not establish causation.

## Dataset Reference

Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). *Wine Quality* [Dataset]. UCI Machine Learning Repository.

**Dataset DOI:** https://doi.org/10.24432/C56S3T

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0).

Please retain appropriate attribution when sharing or adapting the dataset.

## 👤 Author

Presley Ufuoma Sergine
Data Analyst | Lagos, Nigeria

<p>
  <a href="https://www.linkedin.com/in/presley-sergine-b9176343a">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:presleysergine23@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center">
