# Hospital Readmission Risk Prediction

- Goal: Built a machine learning model to predict 30-day hospital readmission risk.

- Extracted and integrated ICU stays, labs, procedures, medications, and demographics using SQL + BigQuery from mimic-iii clinical database via physionet

- Conducted univariate and bivariate analysis to identify key risk factors: e.g., Medicare insurance, diabetes, CHF, comorbidity score, and prior admissions.

- Engineered a custom risk scoring metric and classified patients into low, moderate, and high-risk groups.

- Trained a logistic regression model using Python (scikit-learn) with: Class imbalance handling,Threshold tuning and Achieved ~86% accuracy and high recall for the high-risk group

- Exported model outputs to CSV for dashboard integration.

- 📊 Tableau Dashboard: https://public.tableau.com/app/profile/madhu.chavali2213/viz/readmissionrisk/Dashboard1
