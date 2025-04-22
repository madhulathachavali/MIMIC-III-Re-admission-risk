# MIMIC-III-hospital-resource-utilization

- Developed an end-to-end ETL pipeline in BigQuery using MIMIC-III clinical data to analyze hospital resource utilization. 
- Combined ICU stays, procedures, labs, medications, and demographics per hospital admission. 
- Built Tableau dashboards to visualize length of stay, ICU hours, and treatment patterns across patient cohorts.(Average ICU hours per diagnosis, Resource usage by age and gender, LOS vs procedures or meds,Top diagnoses with highest ICU burden)

Data Source: Johnson, A., Pollard, T., & Mark, R. (2019). MIMIC-III Clinical Database Demo (version 1.4). PhysioNet. https://doi.org/10.13026/C2HM2Q.

Original publication:
Johnson, A. E. W., Pollard, T. J., Shen, L., Lehman, L. H., Feng, M., Ghassemi, M., Moody, B., Szolovits, P., Celi, L. A., & Mark, R. G. (2016). MIMIC-III, a freely accessible critical care database. Scientific Data, 3, 160035.

PhysioNet: Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.


Hospital Readmission Risk Prediction | MIMIC-III | Python, SQL, BigQuery, Tableau

Extracted and integrated ICU stays, labs, procedures, medications, and demographics data per hospital admission from the MIMIC-III database using SQL and Google BigQuery.

Performed univariate and bivariate analysis to identify key predictors of readmission, including Medicare insurance, diabetes, CHF, comorbidities, and admission history.

Engineered a custom risk scoring metric and categorized patients into low, moderate, and high-risk groups.

Built and evaluated logistic regression models in Python (scikit-learn) with class balancing and threshold tuning, achieving ~86% accuracy and high recall for the high-risk group.
