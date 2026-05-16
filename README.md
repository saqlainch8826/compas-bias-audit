# COMPAS Bias Audit
Racial bias audit of the COMPAS recidivism risk assessment system using ProPublica's Broward County dataset.

## Policy Question
Does COMPAS produce different misclassification rates for African-American and Caucasian defendants in criminal risk prediction?

## Method
* Data Source: ProPublica's COMPAS two-year recidivism dataset
* Tools Used: Python, Pandas, Matplotlib, Google Colab
* Metrics Computed: False Positive Rate (FPR) and False Negative Rate (FNR) by race after applying ProPublica-style filtering

## Key Finding
Across 3,696 African-American defendants and 2,454 Caucasian defendants, the false positive rate was 44.8% for African-American defendants and 23.5% for Caucasian defendants. The false negative rate was 28.0% for African-American defendants and 47.7% for Caucasian defendants.

## Files
- `COMPAS_Algorithmic_Bias_Audit.ipynb` — full analysis notebook with code, findings, and policy discussion
- `compas_bias_chart.png` — bar chart of FPR and FNR by race group
