# Regression diagnostics and influential observations

## Regression checklist
- Model specification and predictor/outcome definitions.
- Linearity and functional form.
- Residual distribution and heteroskedasticity.
- Multicollinearity (VIF/tolerance, interpreted contextually).
- Leverage and influence (Cook's distance and complementary diagnostics).
- Robust standard errors or alternative estimators where justified.

## Influential observations
An influential case is not automatically an invalid case. Check:
1. Was the respondent eligible?
2. Is there evidence of careless responding, impossible values, duplicate participation, or data corruption?
3. Is the observation valid but unusual?
4. Does the model depend heavily on it?
5. Do conclusions change in a transparent sensitivity analysis?

Retain valid observations in the primary analysis unless independent data-quality or pre-specified exclusion criteria justify removal. Report sensitivity analyses without presenting case deletion as a way to obtain significance.

## Case illustration
In the N=50 pilot regression, four observations were flagged as relatively influential. Excluding them changed the IM coefficient's direction and significance, while ADI remained positively associated with IT. The four cases were retained because no independent data-quality reason for exclusion had been established. The original report did not provide individual Cook's D values or the threshold; do not infer or fabricate them.
