# Traffic Accident Severity Prediction (CA / NY / FL)

## Why this matters (Business Value)
This project helps transportation agencies and city planners prioritize high-impact safety interventions by identifying the conditions and roadway features most associated with severe crashes across three states. The results support targeted actions (e.g., improving lighting/signage at intersections and strengthening signal enforcement) to reduce severe outcomes and guide infrastructure investment.

## Overview
I built an end-to-end machine learning pipeline to predict accident severity using **Logistic Regression**, **Random Forest**, and **XGBoost**. The workflow includes data cleaning, exploratory data analysis (EDA), feature engineering, and model evaluation.

## Key Results
- **Best model:** XGBoost  
- **Accuracy (held-out test):** **~71% (CA)**, **~63% (NY)**, **~72% (FL)**
- **Most influential factors:** visibility conditions and roadway infrastructure (e.g., intersections/crossings) were stronger predictors than adverse weather

## Actionable Recommendations
Based on the analysis, the most practical interventions include:
- Improve **lighting** and **signage** in poor-visibility areas
- Prioritize safety upgrades at **intersections/crossings**
- Strengthen **traffic signal enforcement** and compliance measures

## Methods (High Level)
- Data cleaning + encoding
- Feature engineering: time-of-day, infrastructure indicators, visibility-related conditions
- Model comparison: Logistic Regression vs Random Forest vs XGBoost
- Model evaluation: accuracy and error analysis (plus any additional metrics you include)

## Repo Structure
├── notebooks/ # EDA + modeling notebooks (clean, numbered)
├── src/ # reusable code (prep, features, train, eval)
├── reports/ # final report PDF and figures
├── figures/ # charts used in README/report
├── requirements.txt # or environment.yml
└── README.md


## How to Run
1. Create environment:
   ```bash
   pip install -r requirements.txt


