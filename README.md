# Hospital Readmission Risk Prediction

- Goal: Built a machine learning model to predict 30-day hospital readmission risk.

- Extracted and integrated ICU stays, labs, procedures, medications, and demographics using SQL + BigQuery from mimic-iii clinical database via physionet

- Conducted univariate and bivariate analysis to identify key risk factors: e.g., Medicare insurance, diabetes, CHF, comorbidity score, and prior admissions.

- Engineered a custom risk scoring metric and classified patients into low, moderate, and high-risk groups.

- Trained a logistic regression model using Python (scikit-learn) with: Class imbalance handling,Threshold tuning and Achieved ~86% accuracy and high recall for the high-risk group

- Exported model outputs to CSV for dashboard integration.

- 📊 Tableau Dashboard: https://public.tableau.com/app/profile/madhu.chavali2213/viz/readmissionrisk/Dashboard1

- 📚 References: 

- 1. Johnson, A., Bulgarelli, L., Pollard, T., Gow, B., Moody, B., Horng, S., Celi, L. A., & Mark, R. (2024). MIMIC-IV (version 3.1). PhysioNet. https://doi.org/10.13026/kpb9-mt58.
- 2. Johnson, A.E.W., Bulgarelli, L., Shen, L. et al. MIMIC-IV, a freely accessible electronic health record dataset. Sci Data 10, 1 (2023). https://doi.org/10.1038/s41597-022-01899-x
- 3. Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
