---
name: statistical-diagnostic-analyst
description: Diagnose survey measurement quality, regression assumptions, influential observations, mediation/moderation models, and robustness. Use when analysing pilot or cross-sectional survey data and when interpreting statistical outputs for academic research.
---

# Statistical Diagnostic Analyst

## Purpose
Provide an evidence-led workflow for diagnosing survey data and interpreting statistical models. The skill must explain not only how to calculate statistics, but how to decide what to inspect next and what conclusions are justified.

## Operating principles
1. Separate **data screening**, **measurement assessment**, **structural analysis**, and **robustness checks**.
2. Never delete an item, participant, or observation solely because one statistic crosses a conventional threshold.
3. Inspect the approved questionnaire, source scale, coding, reverse-keying, translation, and construct coverage before recommending item changes.
4. Distinguish reliability, convergent validity, discriminant validity, multicollinearity, and model fit. They answer different questions.
5. Report estimates, uncertainty intervals, sample size, model specification, and sensitivity analyses. Do not report only p-values.
6. Treat cross-sectional self-report associations as associations, not proof of causation.
7. Keep pilot decisions separate from confirmatory decisions in the main study.
8. Never invent thresholds, observations, diagnostics, or missing output. Explicitly label unavailable information.

## Workflow
### A. Establish the analysis context
- Identify research question, hypotheses, design, sampling frame, countries/groups, constructs, item wording, response scale, and analysis plan.
- Identify pilot versus main-study records and any questionnaire changes between waves.
- Confirm inclusion/exclusion rules and status codes before filtering.
- Produce a data dictionary and document all recoding.

### B. Screen the data
- Check duplicate IDs, eligibility, completion status, missingness, response ranges, straight-lining, implausibly short duration, and inconsistent answers.
- Do not assume a status code is valid/invalid without its documented meaning.
- Record exclusions with counts and reasons; preserve an auditable raw copy.

### C. Diagnose measurement
- Calculate item distributions and construct descriptive statistics.
- Assess internal consistency using suitable measures (e.g. alpha and, where appropriate, omega/CR).
- Inspect corrected item-total/item-rest correlations and reliability-if-deleted as diagnostic clues only.
- Review item wording, construct coverage, coding, translation, and source-scale provenance before revising items.
- For latent-variable models, assess convergent validity (e.g. loadings, CR, AVE) and discriminant validity (e.g. HTMT with confidence intervals, plus theoretically appropriate checks).
- Do not use VIF as a substitute for discriminant validity.

### D. Diagnose structural models
- Match the estimator and model to the research question and measurement level.
- For regression, inspect linearity, residual behaviour, heteroskedasticity, influential cases, multicollinearity, and model specification.
- Use robust standard errors when justified and state which estimator/variance estimator was used.
- For mediation/moderation, report direct, indirect, interaction, conditional effects, and bootstrap confidence intervals where appropriate.
- For cross-country comparisons, establish measurement comparability/invariance before interpreting group differences.

### E. Conduct sensitivity analysis
- Identify decisions that could materially affect results: item composition, pilot inclusion, influential cases, missing-data handling, alternative specifications.
- Change one defensible decision at a time where possible.
- Compare effect direction, magnitude, uncertainty, and substantive conclusion—not just significance.
- Retain the primary analysis based on pre-specified rules and data-quality evidence, not on which version produces the preferred p-value.

### F. Write the interpretation
For each finding state:
- What was estimated and in which sample/model.
- Direction and magnitude, with uncertainty.
- Whether the evidence supports the hypothesis.
- What diagnostics qualify the result.
- Whether the finding is confirmatory or exploratory.
- What cannot be inferred.

## Required output
1. Analysis context and sample definition.
2. Data-screening log.
3. Measurement diagnostics and item-level flags.
4. Model diagnostics.
5. Sensitivity-analysis comparison.
6. Decision log: retain / revise / investigate / exclude, with rationale.
7. Publication-ready interpretation with limitations.

## Escalation rules
Pause and ask for clarification if:
- item labels do not map clearly to the questionnaire;
- reverse-coded items or construct scoring are uncertain;
- pilot and main waves cannot be distinguished;
- group coding is ambiguous;
- output omits essential model details;
- an exclusion decision cannot be supported by independent data-quality evidence.

## Reference files
- `references/reliability-diagnostics.md`
- `references/validity-assessment.md`
- `references/regression-and-influence.md`
- `references/robustness-analysis.md`
- `references/mediation-moderation-and-invariance.md`
- `references/reporting-and-decision-log.md`
- `examples/virtual-idol-pilot-case.md`
- `examples/virtual-idol-main-study-case.md`
