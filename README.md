# Summary
A survival analysis evaluating hormone therapy for disease-free survival (DFS) in 686 patients. Hormone therapy reduced event risk by 40% (HR = 0.60, p < .001). Prognostic group was also a strong predictor, while chemotherapy was not significant.

# Results

Primary Cox model:
- Hormone therapy (vs SOC): HR = 0.59 (95% CI: 0.50 - 0.70), p < .001
- Prognostic group Medium (vs Good): HR = 2.04 (95% CI: 1.64 - 2.54), p < .001
- Prognostic group Poor (vs Good): HR = 3.11 (95% CI: 2.49 - 3.90), p < .001
- Chemotherapy (Yes vs No): HR = 1.05 (95% CI: 0.86 - 1.29), p = .627

Sensitivity analysis (stratified Cox model):
- Hormone therapy HR = 0.60 (95% CI: 0.51 - 0.71), p < .001

Summary statistics:
- Total patients: 686 (342 SOC, 344 HT)
- Events: 543
- Median follow-up: 1,506 days
- Log-rank test: χ² = 26.8, p < .001

# Methods

Kaplan-Meier curves and log-rank test were used for unadjusted comparison of survival between treatment arms. A Cox proportional hazards model was fitted with treatment arm, prognostic group, and chemotherapy as predictors. The proportional hazards assumption was tested using Schoenfeld residuals. Violations were detected for prognostic group (p = .024) and chemotherapy (p < .001), so a stratified Cox model was fitted as a sensitivity analysis, allowing each combination of prognostic group and chemotherapy to have its own baseline hazard while estimating a common treatment hazard ratio. Likelihood ratio tests were used for model comparison.