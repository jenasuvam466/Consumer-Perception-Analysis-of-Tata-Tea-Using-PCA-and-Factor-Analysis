# Consumer-Perception-Analysis-of-Tata-Tea-Using-PCA-and-Factor-Analysis
This project uses dimension-reduction and regression techniques to condense a 24-item consumer survey into a small set of interpretable factors, then tests which of those factors best predict overall customer satisfaction.

A Python-based multivariate analysis of survey data from **268 respondents** to uncover the key drivers of consumer perception and satisfaction toward Tata Tea.

## Overview

This project uses dimension-reduction and regression techniques to condense a 24-item consumer survey into a small set of interpretable factors, then tests which of those factors best predict overall customer satisfaction.

## Key Highlights

- **Dimension reduction:** Applied Principal Component Analysis (PCA) and Exploratory Factor Analysis (EFA) to reduce 24 survey variables into **4 meaningful components**, together explaining **65.31%** of total variance.
- **Data suitability checks:** Validated the dataset with the Kaiser-Meyer-Olkin (KMO) test (**0.903**) and Bartlett's Test of Sphericity (**p < 0.001**), confirming strong sampling adequacy for factor analysis.
- **Predictive modeling:** Built a regression model on the extracted factor scores to measure each factor's influence on satisfaction.

## Key Findings

| Rank | Factor | Impact on Satisfaction |
|------|--------|------------------------|
| 1 | Quality & Loyalty | Strongest predictor |
| 2 | Value & Availability | Second strongest |
| 3 | Taste & Aroma | Significant contributor |

## Methodology

1. **Data collection:** Survey responses from 268 consumers (24 variables)
2. **Assumption testing:** KMO measure and Bartlett's test
3. **Factor extraction:** PCA and EFA
4. **Factor interpretation:** Labeling components based on variable loadings
5. **Regression analysis:** Satisfaction modeled on factor scores

## Tech Stack

- **Language:** Python
- **Libraries:** pandas, NumPy, scikit-learn, factor_analyzer, statsmodels, matplotlib, seaborn
- **Techniques:** PCA, EFA, KMO, Bartlett's Test, Multiple Linear Regression

## Repository Structure
