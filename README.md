# Lending Club Loan Default Analysis

## Overview

This project performs an Exploratory Data Analysis (EDA) on the Lending Club loan dataset to identify borrower characteristics and loan attributes associated with credit default risk.

The objective is to uncover key factors influencing loan defaults and provide business recommendations that help reduce credit losses while maintaining profitable lending operations.

---

## Business Problem

Financial institutions face two major risks during loan approval:

- Approving loans for borrowers who later default, resulting in financial losses.
- Rejecting creditworthy applicants, leading to missed business opportunities.

Using historical Lending Club data, this project identifies patterns that distinguish risky borrowers from reliable borrowers.

---

## Dataset

The dataset contains historical Lending Club loan records issued between 2007 and 2011.

The repository includes:

- Data Dictionary
- Analysis Notebook
- Source Code
- Final Presentation

**Note:** The original `loan.csv` dataset is not included due to size considerations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

1. Data Cleaning
   - Removed columns with excessive missing values
   - Handled missing observations
   - Converted variables to appropriate data types

2. Feature Engineering
   - Created income buckets
   - Interest-rate buckets
   - Loan-to-income ratio
   - Debt-to-income categories

3. Exploratory Data Analysis
   - Univariate Analysis
   - Segmented Univariate Analysis
   - Bivariate Analysis

4. Business Insights
   - Identified major risk drivers
   - Recommended lending strategies

---

## Key Findings

- Approximately **14%** of approved loans were charged off.
- Loan default risk increases significantly for lower credit grades.
- Borrowers with higher interest rates exhibit higher default rates.
- Small business loans have one of the highest default percentages.
- Lower-income borrowers are more likely to default.
- High debt-to-income (DTI) ratios are associated with increased credit risk.
- Borrowers with previous bankruptcies or derogatory records are considerably riskier.
- High revolving credit utilization (>75%) is linked to higher default rates.

---

## Business Recommendations

- Reduce approvals for high-risk loan grades.
- Limit loan amounts relative to borrower income.
- Apply stricter underwriting for applicants with high DTI ratios.
- Closely evaluate borrowers with previous bankruptcies.
- Monitor revolving credit utilization before loan approval.
- Consider risk-based pricing for higher-risk applicants.

---

## Repository Structure

```
lending-club-loan-default-analysis/
│
├── data/
├── images/
├── notebooks/
├── reports/
├── src/
├── requirements.txt
├── LICENSE
└── README.md
```

---

## Future Improvements

- Predictive machine learning models for loan default prediction.
- Feature importance analysis using tree-based models.
- Interactive dashboards using Power BI or Tableau.
- Explainable AI (SHAP/LIME) for model interpretability.

---

## Author

**Hanaa Parvez Khan**

Data Analytics | Machine Learning | Risk Analytics | Python | SQL
