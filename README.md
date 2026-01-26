# Kaiser_Permanante_Capstone
Capstone Project build with the guidance of Kaiser Permanente team. This project uses CMS Medicare Advantage public data to evaluate CMS policy impacts (Interrupted Time Series) and predict quality outcomes (Star Ratings, HEDIS) with regression and ML models (Ridge, Random Forest, XGBoost). Built in Python. 

# Kaiser Permanente Capstone (CMS Medicare Advantage Analytics)

This repository contains my semester capstone project analyzing public CMS Medicare Advantage data to:
1) estimate the impact of key CMS policy changes using Interrupted Time Series (ITS) methods, and  
2) model plan quality outcomes using regression and machine learning.

This project was conducted as part of a Kaiser Permanente capstone experience and felt like a mini internship because I had the freedom to scope, explore, and iterate on the analysis with weekly stakeholder style check-ins.

## Project Goals (3 Problem Statements)

1. **Policy impact (CA vs HI)**  
   How did major CMS policy changes (2018, 2020, 2022) shift Medicare Advantage outcomes like premiums, MOOP, enrollment, and Star Ratings in California vs Hawaii?

2. **What drives Star Ratings**  
   Which plan and member experience factors best predict Star Ratings, and what variables consistently matter across models?

3. **Predicting clinical quality (HEDIS)**  
   Can HEDIS performance be reliably predicted using the same feature set used for Star Ratings, and how does predictability compare?

## Data Source

- **Centers for Medicare and Medicaid Services (CMS)** public datasets (Medicare Advantage).
- Data was cleaned, merged, and transformed in Python.

Note: This project uses public, aggregate level data and does not contain PHI.

## Methods Used

### Causal and quasi-experimental analysis
- Interrupted Time Series (ITS) / intervention analysis
- CA vs HI comparisons around CMS policy change windows (2018, 2020, 2022)
- Outcomes analyzed include: premiums, MOOP, enrollment, Part D deductible, and Star Ratings

### Predictive modeling
- Linear Regression
- Ridge Regression
- Random Forest
- XGBoost

## Key Outputs

- Reproducible data prep and modeling pipeline in Python
- Model evaluation metrics and feature importance outputs
- Visualizations and summary tables supporting stakeholder style findings

## Libraries used 
- pandas, numpy, matplotlib, scikit-learn, statsmodels, xgboost

## Disclaimer

This repository reflects my personal academic work using public CMS data.
It is not a Kaiser Permanente product and does not represent Kaiser Permanente’s views.4

##Data : https://drive.google.com/file/d/10I3oIFtauRmejiOzp-3D3uSoDk_v69xv/view?usp=sharing
   
