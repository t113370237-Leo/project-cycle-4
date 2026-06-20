# Final Individual Project: Regression Statistical Report

**Dataset:** `cleaned_yrbs_master.csv`
**Research Question:** Multiple Linear Regression with Control Variable
**Responsible Person:** 李宥宣 (113370237)

## 1. Model Overview
* **Dependent Variable:** `BMIPCT` (BMI Percentile)
* **Control Variable:** `AerobicExercise`
* **Independent Variable:** `Threat_Group` (Reference: 0 times)
* **Total Observations:** 11541

## 2. Model Fit Statistics
* **R-squared:** 0.0016
* **Adjusted R-squared:** 0.0013
* **F-statistic:** 6.1331 (p-value: 3.6626e-04)
*(The overall model is statistically significant).*

## 3. Key Findings & Conclusion
* **Control Variable Impact:** Aerobic exercise has a negative coefficient, indicating that increased exercise is associated with a lower BMI percentile, which aligns with logical expectations.
* **Main Effect Robustness:** Even after controlling for aerobic exercise, the frequency of weapon threats (specifically the '2+ times' group) **remains statistically significant** in predicting higher BMI percentiles. 

**Conclusion:** The positive relationship between severe school safety threats and higher BMI percentiles is robust and cannot be solely explained by differences in exercise habits.
