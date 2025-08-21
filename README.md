# **TELCO CUSTOMER CHURN ANALYSIS**

## Repository Outline
1. **README.md**                       - Project Overview
2. **Notebook.ipynb**   - The Python notebook contains data cleaning and statistical analysis.


## Problem Background
The telecommunications company is experiencing an elevated customer churn rate, particularly within the month-to-month contract segment. An incomplete understanding of churned customers’ characteristics has hindered the design of effective retention strategies. Accordingly, this analysis was conducted to uncover patterns and key drivers of churn based on historical customer data.

## Project Output
Project outputs:
- Descriptive and inferential statistical analyses to understand churn behavior
- Interactive dashboard visualizations in Tableau Public
- Data-driven strategic recommendations to reduce churn

## Data
- Dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- Size: 7,043 rows & 21 columns
- Key features: `Churn`, `Contract`, `MonthlyCharges`, `TotalCharges`, `Tenure`, `InternetService`
- Handling: Missing values in TotalCharges were removed after converting the column to a numeric type.

## Method
Main methods used in this project include:
- Descriptive Statistics: analysis of mean, median, distribution, and outliers
- Inferential Statistics: Chi-Square test to examine the relationship between churn and contract type
- Data Visualization: bar plots, boxplots, line charts, etc.

## Stacks
- `Python 3.10`
Libraries:
- `pandas`, `numpy`: for data manipulation
- `matplotlib`, `seaborn`: for statistical visualization

Tools:
- Tableau Public (interactive dashboard)
- Jupyter Notebook

## Reference
- [Dataset]('https://www.kaggle.com/datasets/blastchar/telco-customer-churn')
- [Tableau Public Dashboard]('https://public.tableau.com/app/profile/yunido.baheramsyah/viz/TelcoCustomerChurnAnalysis_17557333951600/TELCOCUSTOMERCHURNANALYSIS?publish=yes')
---