
Risk Model

Flight Progress → 30%
Study Performance → 25%
Payment Behaviour → 30%
Operational Delays → 15%

Final Risk Score =
(Flight Risk × 0.30)
+
(Study Risk × 0.25)
+
(Payment Risk × 0.30)
+
(Delay Risk × 0.15)

Risk Levels:
0–39 → Low
40–69 → Medium
70–100 → High


# Methodology and Explainability

## 1. Why did you choose your risk score formula?

The risk score was designed as a transparent weighted model rather than a complex machine learning approach. The objective was to ensure explainability and operational usability. Flight progress, study performance, payment behaviour, and operational delays were combined because they represent practical, academic, financial, and operational dimensions of cadet success.

Risk Formula:

* Flight Progress → 30%
* Study Performance → 25%
* Payment Behaviour → 30%
* Operational Delays → 15%

## 2. Which features had the most impact and why?

The strongest contributors were flight progress and payment behaviour.

Flight progress directly reflects training completion status and operational readiness.

Payment behaviour influences continuity of training and long-term completion risk.

Study performance was included to represent theoretical readiness.

Operational delay was treated as a supporting signal rather than a dominant predictor.

## 3. What assumptions did you make?

* Historical operational patterns are representative.
* Missing values indicate incomplete operational records.
* Payment activity may influence training continuity.
* Study readiness contributes to completion probability.
* Validation findings were treated as indicators and not corrected automatically.

## 4. What data quality issue could mislead the model?

Several issues could distort interpretation:

* Completed sorties without actual timestamps
* Incorrect delay calculations
* Outstanding payment inconsistencies
* Study progress exceeding logical limits
* Flight activity without study participation

These issues may artificially increase or reduce calculated risk.

## 5. What would you not automate or predict yet?

The current model should not automatically:

* Recommend cadet removal
* Rank instructor performance
* Make financial decisions
* Predict final licensing outcomes
* Trigger disciplinary actions

Human review should remain mandatory.

## 6. How would you validate this model with real FTO data?

Validation would include:

* Historical back-testing
* Comparison against actual completion outcomes
* Instructor review sessions
* Monthly calibration of thresholds
* Monitoring prediction consistency over time

## 7. How would you prevent unfair ranking of cadets?

Risk scores should support intervention rather than comparison.

Controls include:

* Avoid public ranking
* Show reasons behind scores
* Allow instructor override
* Refresh scores periodically
* Exclude protected or irrelevant variables

## 8. How should AIRMAN display this insight without demotivating students?

Insights should be displayed as guidance rather than grades.

Recommended approach:

* Use readiness indicators
* Highlight improvement opportunities
* Show actionable recommendations
* Avoid labels such as low performer

## 9. What additional data would improve your model?

Additional useful variables:

* Weather severity
* Simulator performance
* Attendance consistency
* Instructor feedback
* Study session duration
* Assessment outcomes
* Recovery actions

## 10. How would this analysis help Skynet and TOGA become more intelligent products?

Skynet could improve operational decision-making through utilization tracking, delay monitoring, and capacity balancing.

TOGA could become more adaptive through personalized study recommendations, early intervention alerts, and readiness monitoring.

Together, both systems could evolve from reporting platforms into proactive decision-support products.

## Data Cleaning Strategy and Auditability

Data quality issues were identified during validation but source datasets were intentionally preserved and not automatically corrected.

This approach maintains auditability, avoids unsupported assumptions, and ensures reproducible reporting.

Recommended cleaning actions were documented separately in cleaned_outputs.csv for future production governance.
