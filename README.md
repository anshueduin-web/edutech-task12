# Task 12: Feature Engineering

## Internship Details
- **Organization:** Edutech Solution
- **Program:** Data Science Internship
- **Task:** Task 12 — Feature Engineering

## Objective
Apply feature engineering on Housing dataset —
create interaction features, encode categorical data,
and handle skewed features using log transformation.

## Dataset Used
- **Name:** California Housing Dataset (sklearn built-in)
- **Rows:** 20,640 | **Features:** 8

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib

## Steps Performed
1. Loaded California Housing dataset
2. Created interaction features (RoomsPerHousehold, BedroomRatio)
3. Created IncomeGroup categorical column
4. Applied Label Encoding on IncomeGroup
5. Applied One-Hot Encoding on IncomeGroup
6. Checked skewness of Population and Price
7. Applied log transformation to reduce skewness
8. Saved enhanced dataset

## Key Findings
- Population skewness reduced significantly after log transform
- One-Hot encoding created 4 new dummy columns
- New interaction features add predictive value

## Files
| File | Description |
|------|-------------|
| task12_feature_eng.ipynb | Full notebook |
| enhanced_dataset.csv | Final enhanced dataset |
| log_transform.png | Before/after skewness graphs |
| README.md | Documentation |

## Learning Outcome
Learned how feature engineering improves model performance
through encoding, interaction features, and log transformation.
