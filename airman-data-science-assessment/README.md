# AIRMAN Data Science Technical Assessment

## Project Overview

This project analyses Flight Training Organization (FTO) operational, training, study, and financial performance using simulated AIRMAN datasets.

The objective was to evaluate operational efficiency, identify cadet training risks, generate study intelligence, assess financial continuity risks, and produce explainable recommendations for leadership decision-making.

The project includes data validation, analytics, explainable risk scoring, visual reporting, and executive insights.

---

## Tools / Libraries Used

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Matplotlib

Environment:

* Jupyter Notebook
* VS Code

---

## Setup Instructions

1. Extract project files.
2. Open project folder in VS Code.
3. Install required packages:

```bash
pip install pandas numpy matplotlib
```

4. Verify folder structure:

```text
airman-data-science-assessment/
```

5. Open:

```text
notebooks/analysis.ipynb
```

---

## How to Run the Notebook

1. Launch Jupyter Notebook.
2. Open `analysis.ipynb`.
3. Run cells sequentially from Task 1 to Task 8.
4. Generated outputs will automatically appear in:

```text
reports/
charts/
data/
```

---

## Data Assumptions

The following assumptions were used:

* Historical operational behaviour represents realistic training patterns.
* Missing values indicate incomplete operational records.
* Payment behaviour may influence training continuity.
* Study readiness contributes to training completion.
* Risk thresholds were designed for explainability.
* Source datasets were preserved and not automatically modified.

---

## Metrics Calculated

Operational Metrics:

* Aircraft Utilization
* Instructor Utilization
* Dispatch Reliability
* Completion Rate
* Delay Analysis

Training Metrics:

* Flight Progress %
* Remaining Flight Hours
* Completion Risk

Study Metrics:

* Study Readiness
* Quiz Performance
* Inactivity Risk

Financial Metrics:

* Outstanding Amount
* Payment Completion %
* Continuity Risk

Risk Metrics:

* Explainable Cadet Risk Score

---

## Risk Score Explanation

Risk Score Formula:

* Flight Progress → 30%
* Study Performance → 25%
* Payment Behaviour → 30%
* Operational Delay → 15%

Risk Levels:

* 0–39 → Low
* 40–69 → Medium
* 70–100 → High

---

## Key Outputs

Generated Reports:

```text
reports/data_quality_report.md
reports/skynet_operations_analysis.md
reports/training_progress_analysis.md
reports/toga_study_intelligence.md
reports/finance_risk_analysis.md
reports/executive_insights.md
reports/methodology.md
```

Generated Data:

```text
data/risk_scores.csv
data/cleaned_outputs.csv
```

Generated Charts:

```text
charts/
```

including utilization, training, study, finance, and risk visualizations.

---

## Known Limitations

* Dataset size is limited.
* Risk thresholds are manually selected.
* No real-world operational validation.
* Temporal forecasting was not included.
* Cleaning recommendations were documented but not automatically applied.

---

## What I Would Improve With More Time

* Refine validation rules using additional business scenarios.
* Improve risk score thresholds using historical training outcomes.
* Add more interactive filtering and dashboard views.
* Expand analysis with additional operational variables such as weather and attendance.
* Perform testing using larger and more realistic datasets.

---

## AI Usage and Verification

AI tools were used to accelerate code generation, structure design, and documentation support.

Outputs were verified manually through:

* Dataset inspection
* Validation rule checks
* Cross-checking calculations
* Reviewing generated reports
* Confirming business-rule consistency

Final decisions, interpretation, and submission structure were reviewed and adjusted manually.


## AI Usage Disclosure

### 1. Did you use AI tools? If yes, where?
Yes. AI tools were used to support documentation, structure the workflow, review outputs, and improve clarity during the assessment process.

### 2. What prompts or tasks did AI help with?
- Organizing project folders and files
- Refining explanations and written summaries
- Reviewing output presentation
- Improving documentation readability
- Suggesting repository organization

### 3. Which parts did you personally verify?
- Dataset preparation and organization
- Generated charts and observations
- Report content and final outputs
- Repository structure and uploaded materials

### 4. Which AI suggestion did you reject or modify?
Some generated explanations and descriptions were edited to better reflect the actual analysis and avoid unsupported conclusions.

### 5. Which part of the analysis are you least confident about?
The interpretation of observed patterns may benefit from additional validation and expanded assumptions.

### 6. Pick one formula or chart and explain it in your own words.
Example – Cadet Progress Chart:
This chart shows how performance changes across different stages. A higher value represents stronger progress, while lower values indicate areas that may require additional attention or improvement.
