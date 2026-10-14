# Insurance_Charge_pred_Linear-Regression
Insurance charges prediction using linear regression: data cleaning, EDA, and model building with scikit-learn.
# Insurance Charges Prediction

Predicting medical insurance charges from personal details using linear regression.

## Overview
This project builds a regression model that estimates individual medical insurance charges based on features such as age, sex, BMI, number of children, smoking status, and region. It covers the full workflow: data cleaning, exploratory data analysis (EDA), model building, and evaluation.

## Dataset
- Source: [Kaggle dataset insurance charges]
- Target: `charges`

## Workflow
1. **Data cleaning:**checked for missing values and duplicates, fixed data types
2. **EDA:** explored feature distributions and their relationship with charges using plots
3. **Preprocessing:** encoded categorical columns such as sex, smoker, region
4. **Modeling:** trained a Linear Regression model with scikit-learn on an [80/20] train-test split
5. **Evaluation:** measured performance on the test set

## Key Findings
-  Smokers pay significantly higher charges than non-smokers
- Charges tend to increase with age
- Higher BMI is associated with higher charges, especially for smokers



## Limitations & Next Steps
- A linear model can't fully capture non-linear effects (e.g. the combined effect of smoking and BMI).
- Next, I plan to try Polynomial Regression and Random Forest to compare performance.

## Tech Stack
Python, pandas, NumPy, matplotlib / seaborn, scikit-learn, Jupyter Notebook

## How to Run
1. Clone this repository
2. Download the dataset from the Kaggle link above and place it in the project folder
3. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
4. Open it in Jupyter and run all cells
