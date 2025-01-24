# Caravan-Insurance-Policy-Analysis
A statistical and machine learning project analyzing customer data from the Insurance Company Benchmark (COIL 2000) dataset. The project focuses on predicting caravan insurance purchase likelihood, grouping policyholders into clusters based on demographic attributes, and identifying relationships between caravan insurance and other policy types.


## Overview
This project analyzes customer data from the Insurance Company Benchmark (COIL 2000) dataset using statistical and machine learning methods. The goal is to:
- Predict the likelihood of a customer purchasing caravan insurance.
- Group policyholders into clusters based on demographic and product purchase attributes.
- Explore relationships between caravan insurance and other insurance types.

## Dataset
- **Source**: [UCI Machine Learning Repository - COIL 2000](https://archive.ics.uci.edu/ml/datasets/Insurance+Company+Benchmark+%28COIL+2000%29)
- **Description**:
  - 86 attributes, including socio-demographic data and product usage.
  - Training dataset: 5,822 observations.
  - Test dataset: 4,000 observations.

## Methodology
- **Predictive Modeling**:
  - Applied Random Forest and Logistic Regression for prediction.
  - Compared models using ROC curves and confusion matrices.
- **Clustering**:
  - Used K-means, hierarchical clustering, and PCA for customer segmentation.
- **Statistical Tests**:
  - Chi-squared tests to identify relationships between caravan insurance and other policy types.

## Tools and Technologies
- **Python**: pandas, numpy, scikit-learn, matplotlib, seaborn.
- **R**: ggplot2, plotly, corrplot, Boruta, and stats libraries.

## Key Findings
1. **Predictive Models**: Logistic Regression performed better than Random Forest with a true positive rate of 52%.
2. **Clustering**: PCA and K-means identified clusters of customers based on income, family size, and insurance types.
3. **Chi-squared Tests**: Strong relationships identified between caravan insurance and private third-party, car, and fire policies.


