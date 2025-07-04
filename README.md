# BNPL Default Analysis

This project analyzes borrower data from Lending Club to identify factors that predict default on Buy Now, Pay Later (BNPL)-type loans.

## Objective

To determine which borrower characteristics are most indicative of default using traditional econometric techniques and modern machine learning methods.

## Data

- Source: [Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club) from Kaggle
- Focus: Credit attributes, income, debt levels, loan purpose, and more

## Methodology

Techniques used:
- **Logistic Regression**
- **Linear Probability Model (LPM)**
- **Random Forest Classifier**
- **Neural Networks**
- **K-Means and Hierarchical Clustering** (for borrower segmentation)

Tools:
- **R**: Data preprocessing, modeling, clustering
- **SAS**: Regression analysis and model comparison

## Folder Structure

- `R_Code/`: Scripts for model building, clustering, and evaluation in R
- `SAS_Code/`: SAS scripts for regression and predictive analysis
- `BNPL Case Study.pdf`: A summary report of the project, findings, and visuals

## Results (Summary)

- Logistic regression and random forests provided the highest predictive power.
- Key predictors of default include debt-to-income ratio, loan purpose, and revolving balance.
- Clustering revealed distinct borrower risk segments.

## Future Work

- Incorporate additional credit data sources
- Expand to time-series risk analysis or macroeconomic shocks
- Deploy as a scoring API using R Shiny or Flask

## Author

Ryan Leddy  
[LinkedIn](https://www.linkedin.com/in/ryanleddy) | [GitHub](https://github.com/ryanleddy)
