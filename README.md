# Chronic Kidney Disease (CKD) Analysis

This project is an exploratory data analysis (EDA) and logistic regression study on a **Chronic Kidney Disease (CKD)** dataset.  
The main objective is to identify clinical and laboratory variables associated with CKD, and to build a multivariate logistic regression model.

## Dataset
The dataset used in this project is a publicly available CKD dataset [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease). It contains both numerical and categorical variables. The target variable is `class` (CKD vs Not CKD).

## Methods
The analysis was carried out in **R** and includes:
1. **Data cleaning**: handling missing values, recoding categorical variables.
2. **Exploratory Data Analysis (EDA)**:  
   - Distribution of variables.  
   - Correlation between predictors.  
   - Relationship with CKD status.  
3. **Multivariate Logistic Regression**:  
   - Categorical variables were binarized (dummy encoding).  
   - Odds Ratios (OR) were computed for interpretability.  
   - Variables such as albumin, pus cell, and diabetes mellitus showed significant associations with CKD.  

## Requirements
- R (≥ 4.0)
- Packages: `tidyverse`, `knitr`, `broom`, `ggplot2`, `fastDummies`, `dplyr`, `logistf`, `patchwork`

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the Rmarkdown in RStudio or VS Code.

3. Run the analysis step by step.

## Notes

- This project is part of **my data analysis portfolio**.

- The goal was not to build machine learning models, but to perform exploratory analysis and multivariate logistic regression.
