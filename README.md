# credit_risk_shap-and-lime-for-Machine-Learning

1. Data Preprocessing

You cleaned the dataset:

Handled missing values

Scaled numerical features

Prepared the data for modeling
This step ensures the model receives clean and consistent inputs.

2. Model Development

You trained a non-linear classifier (like XGBoost or LightGBM) to predict loan default.
You also:

Tuned the model

Evaluated using cross-validation

Reported AUC, Precision, Recall, F1-Score

This gives a strong and reliable prediction model.

3. SHAP Global Interpretation

Using SHAP:

You calculated which features influence the model most

Created SHAP summary plots

Identified the top drivers of loan default

This explains how the model makes decisions overall.

4. Local Interpretation (SHAP vs LIME)

For 3 individual loan cases (approved, denied, borderline):

You generated SHAP force plots

You generated LIME explanations

Then compared both methods

This shows why the model predicted default risk for each customer.

✅ Final Deliverables You Completed

Python code for the whole pipeline

Performance metrics summary

Written SHAP global feature explanation

Local explanation comparison (SHAP vs LIME)
