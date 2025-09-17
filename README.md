# Insurance Charges Analysis

## Overview
This project analyzes a dataset containing medical insurance cost information for 1,338 individuals in the US. It explores how demographic and health-related variables such as age, sex, BMI, number of children, smoking status, and region affect insurance charges.

The main goal is to test the hypothesis:

> *Smoking status and BMI are the strongest predictors of higher medical insurance charges, even after controlling for age, sex, number of children, and region.*

## Dataset
The dataset includes the following columns:

- `age`: Age of the primary beneficiary (int)
- `sex`: Gender of beneficiary (male, female)
- `bmi`: Body Mass Index (float)
- `children`: Number of children covered (int)
- `smoker`: Smoking status (yes, no)
- `region`: Residential region in the US (northeast, northwest, southeast, southwest)
- `charges`: Medical insurance cost billed (float)

## Analysis Steps
1. Data preprocessing: encoding categorical variables, optional log-transform of charges
2. Exploratory Data Analysis (EDA): distributions, scatter plots, boxplots
3. Correlation analysis: heatmap to visualize relationships between variables
4. Regression modeling:
   - OLS (Ordinary Least Squares) to interpret coefficients and p-values
   - Lasso regression for feature selection
   - Random Forest for non-linear feature importance
5. Model evaluation: RMSE, R², residual analysis
6. Robustness checks: outlier removal, bootstrap confidence intervals, interaction terms

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

## Usage
1. Clone this repository
2. Open `insurance_charges_analysis.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells sequentially to reproduce the analysis

## License
[CC0 1.0 Public Domain] 
