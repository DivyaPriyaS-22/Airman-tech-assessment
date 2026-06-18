
# Executive Insight Report

Data quality issues were identified and documented during validation, but source datasets were intentionally preserved and not automatically corrected. This approach maintains auditability, avoids introducing unsupported assumptions, and ensures that operational reporting remains reproducible. Recommended correction actions were recorded separately in `cleaned_outputs.csv` for future governance and production implementation.

## 1. Top 5 Operational Insights

1. Aircraft utilization varied significantly across bases, indicating uneven operational efficiency.

2. Certain aircraft showed elevated defect occurrence and require operational review.

3. Cancellation patterns were concentrated around a limited number of reasons.

4. Instructor allocation appeared imbalanced with potential workload bottlenecks.

5. Delay behaviour showed measurable impact on sortie completion.


## 2. Top 5 Training Progress Insights

1. Cadet progress rates varied considerably across the cohort.

2. Several cadets remain significantly below expected completion trajectory.

3. Lower study readiness frequently aligned with lower flight progress.

4. Instructor concentration may affect training throughput.

5. Progress variability indicates need for targeted intervention.


## 3. Top 3 TOGA Personalization Opportunities

1. Recommend adaptive study plans based on quiz performance.

2. Trigger reminders for cadets with declining study activity.

3. Personalize chapter sequencing based on training stage.


## 4. Top 3 Finance Risks

1. High outstanding balances may delay training completion.

2. Older payment activity correlates with continuity concerns.

3. Financial exposure should be monitored alongside training performance.


## 5. Product Recommendations for Skynet

1. Real-time operational utilization dashboard.

2. Automated aircraft risk monitoring.

3. Instructor workload balancing engine.


## 6. Product Recommendations for TOGA

1. Personalized readiness scoring.

2. Early intervention recommendation system.

3. Predictive study completion monitoring.


## 7. Data Quality Issues Found

1. Missing operational timestamps.

2. Delay mismatches.

3. Payment inconsistencies.

4. Study progress above logical limits.

5. Missing study activity.


## 8. Suggested Additional Data Fields

1. Weather severity index

2. Instructor feedback score

3. Cadet attendance score

4. Simulator hours

5. Study session duration

6. Recovery actions


## 9. Final Recommendation to AIRMAN Leadership

AIRMAN should combine operational, training, study, and financial intelligence into one explainable monitoring layer. Early intervention and transparent risk communication are recommended over reactive management.
