# Risk-Factors-Associated-with-Stroke-in-an-Adult-Population
Risk Factors Associated with Stroke in an Adult Population derived from DB - https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset


Assignment 1 — Data Quality Assessment

Before any analysis, answer:

1. Dataset Structure

Report:

Number of observations
Number of variables
Variable types
Missing values
Duplicate patients
Impossible values
Outliers
2. Data Dictionary

Create a professional table containing:

Variable name
Definition
Data type
Clinical meaning
Expected range
3. Missing Data Assessment

Questions:

Which variables contain missing data?
Percentage missing?
Is missingness random?
Should we remove or impute?
Which imputation strategy is appropriate?

Support your decision.

4. Data Cleaning Report

Document every transformation.

Example:

Removed duplicates
BMI imputed by median
Converted categorical variables to factors
Checked impossible ages
Standardized gender labels

Nothing should happen silently.

Assignment 2 — Descriptive Analysis

Produce descriptive statistics for every variable.

For continuous variables:

Mean
Median
SD
IQR
Min
Max

For categorical variables:

Frequency
Percentage

Then answer:

Which variables appear abnormal?

Assignment 3 — Population Characteristics

Create baseline characteristics comparing:

Stroke = Yes

vs

Stroke = No

Include:

Age
Gender
BMI
Glucose
Smoking
Hypertension
Heart Disease
Marital Status
Residence
Work Type

This becomes Table 1.

Assignment 4 — Clinical Questions

These are what management actually wants answered.

Question 1

Is age associated with stroke?

Expected:

Visualization
Statistical test
Effect size
Interpretation
Question 2

Do hypertensive patients have higher stroke risk?

Include:

Risk ratio or odds ratio
Confidence interval
Clinical interpretation
Question 3

Does heart disease independently increase stroke risk?

Question 4

Does BMI influence stroke?

If yes,

How?

Linear?

Threshold?

U-shaped?

Question 5

Does elevated glucose predict stroke?

This is likely important.

Explore thoroughly.

Question 6

Does smoking status increase stroke risk?

Separate:

Former
Current
Never
Unknown
Question 7

Does sex influence stroke?

Male vs Female

Question 8

Urban vs Rural

Any difference?

Question 9

Employment category

Which occupations have highest stroke prevalence?

Question 10

Marital status

Why do married individuals appear to have higher stroke?

Is age confounding this?

Assignment 5 — Correlation Analysis

Create:

Correlation matrix

Then answer:

Which variables cluster together?

Any multicollinearity?

Assignment 6 — Statistical Testing

Choose appropriate tests.

Examples:

Continuous

t-test
Mann–Whitney U

Categorical

Chi-square
Fisher's Exact

Explain why each test was chosen.

Assignment 7 — Logistic Regression

Primary endpoint:

Stroke

Predictors:

Age
Gender
BMI
Glucose
Smoking
Hypertension
Heart Disease
Marriage
Residence
Work Type

Report:

Odds ratios
95% confidence intervals
p-values
Clinical interpretation
Assignment 8 — Model Diagnostics

Evaluate:

ROC Curve
AUC
Sensitivity
Specificity
Precision
Recall
Calibration (if appropriate)
Assignment 9 — Variable Importance

Identify:

Top 10 predictors.

Rank them.

Explain clinically.

Assignment 10 — Subgroup Analyses

Perform analyses for:

Patients aged:

<40
40–60

60

Male

Female

Hypertensive

Non-hypertensive

Heart disease

No heart disease

Assignment 11 — Visualization Package

Produce publication-quality figures:

Age distribution
BMI distribution
Glucose distribution
Stroke prevalence by age group
Stroke by smoking
Stroke by hypertension
Stroke by heart disease
Forest plot of odds ratios
ROC curve
Correlation heatmap
Missing data heatmap
Boxplots of continuous variables by stroke status

Every figure should have clear titles, labeled axes, appropriate legends (where applicable), and be suitable for inclusion in a report.

Assignment 12 — Executive Summary

Write a concise report (2–3 pages) for hospital leadership covering:

Key findings
Clinical implications
Recommendations for screening
Recommendations for preventive programs
High-risk populations
Limitations of the analysis
Suggested future work

This summary should be understandable to clinicians and administrators without statistical expertise.
