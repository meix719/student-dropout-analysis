# Student Dropout Risk & Intervention Prioritization

## Overview
Academic team project analyzing a course-provided Caldwell University dataset of 450 student records to support student retention decisions.

The project explores dropout risk, credits completed at withdrawal, and how limited advising resources could be allocated.

## My Contribution
- Conducted Excel analysis of student characteristics and dropout patterns.
- Developed expected value scenarios for proactive retention interventions.
- Contributed recommendations for prioritizing student support.

## Methods
- Excel pivot tables and descriptive analysis
- Multiple linear regression
- Team-developed Random Forest classification
- Expected value and scenario analysis

## Key Findings
- 115 of 450 students withdrew, a dropout rate of 25.6%.
- Part-time students had a higher observed dropout rate than full-time students: 38.9% versus 20.4%.
- The regression explained 57.5% of variation in credits completed at withdrawal among the 115 dropout records.
- The team reported a classification AUC of 0.744, with recall of approximately 30%, highlighting the need for further model improvement.

These findings describe associations and do not establish why students withdrew.

## Expected Value Analysis
The analysis assumed:
- $15,000 in tuition preserved per prevented dropout
- $500 intervention cost per student
- 15 students receiving intervention, including 7 true-positive cases

| Assumed prevention rate among true-positive cases | Expected benefit | Intervention cost | Net expected value |
|---|---:|---:|---:|
| 5% | $5,250 | $7,500 | -$2,250 |
| 10% | $10,500 | $7,500 | $3,000 |
| 20% | $21,000 | $7,500 | $13,500 |

These are illustrative scenarios, not realized savings or measured intervention effects.

## Recommendations
- Pilot targeted outreach before broader implementation.
- Combine academic advising with financial and scheduling support.
- Evaluate intervention outcomes against a comparison group.
- Monitor model performance and fairness across student groups.
- Retain advisor review of all recommendations.

## Project Files
- [Final Report](Final_Report_Group_3.pdf)
- [Final Presentation](Final_Presentation_Group_3.pdf)

## Limitations
- Classification recall was low, leaving many dropout cases unidentified.
- Regression results describe sample fit; performance on new students was not established.
- Credits at withdrawal measure academic progress, not time remaining until withdrawal.
- Intervention effectiveness and financial benefits require pilot validation.
- The original report lists early/late dropout attendance as 73%/79%; workbook calculations give approximately 76%/77%.

## Data
The dataset was provided for coursework. Individual student records are omitted from this repository.

## Team
Mei Qiong Xue, Qunfeng Zhou, Weimin Wu, and Yufei Cai.
