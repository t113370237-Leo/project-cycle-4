# Final Individual Project: Variable Notes & Recoding Rules

**Dataset:** `YRBS_2007.csv`
**Research Question:** Weapon Threat Frequency and BMI Percentile (ANOVA & Regression)

## 1. Independent Variable Definition & Recoding
* **Variable Name:** `WereThreatenedOrInjuredWithAWeaponOnSchoolProperty`
* **Definition:** Used to divide the sample into three independent groups based on the frequency of being threatened with a weapon on school property.
* **Recoding Rules (`Threat_Group`):**
  * Original Code `1` (0 times) -> **Recoded as `0 times`**
  * Original Code `2` (1 time) -> **Recoded as `1 time`**
  * Original Codes `3` through `8` (2 or more times) -> **Recoded as `2+ times`**
  * *Note: Missing values (NaN) or any other invalid codes were dropped.*

## 2. Dependent Variable Definition
* **Variable Name:** `BMIPCT`
* **Definition:** Continuous response variable representing the student's BMI percentile.
* *Note: Missing values (NaN) were dropped.*

## 3. Control Variable Definition (For Multiple Regression)
* **Variable Name:** `AerobicExercise`
* **Definition:** Represents the frequency/days of aerobic exercise, used as a control variable to test the robustness of the weapon threat effect.
* *Note: Missing values (NaN) were dropped.*
