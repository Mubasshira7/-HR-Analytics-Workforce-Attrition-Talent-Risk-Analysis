# -HR-Analytics-Workforce-Attrition-Talent-Risk-Analysis
Workforce Attrition &amp; Talent Risk Analysis project delivering data-driven HR insights. Identified root causes of voluntary turnover, analyzed department-level risk, and built a predictive model to help leadership proactively reduce attrition and improve employee retention strategy.

A technology services company is experiencing rising voluntary attrition (18% annually), especially among mid-level engineering roles.
HR suspects:
1) Compensation gaps
2) Poor manager quality
3) Limited career growth opportunities
However, there is no data-backed validation.
This project applies People Analytics techniques to uncover root causes and build a predictive attrition risk model.


* Attrition is defined strictly as voluntary resignation initiated by the employee.
  The following exit types are excluded from attrition:
      1) Layoffs
      2) Retirements
      3) Internal transfers
   Any employer-initiated separation
Only employees who resigned voluntarily are marked as Attrition = 1.













Weak 3 : Root Cause & Risk Scoring.


# Objective
 The objective of this phase is to:

1)  Identify the key drivers of employee attrition (Root Causes)
2) Build a risk scoring model to predict employees who are likely to leave.

This combines:
* Exit survey text analysis (NLP)
* Rule-based risk scoring

# Root Cause Analysis (Exit Survey NLP) Approach
 > To understand why employees leave, open-ended exit survey comments were analyzed using basic NLP techniques:

 1) Text cleaning (lowercase, punctuation removal)
2) Keyword frequency analysis
3) Theme classification using predefined categories

Theme Classification

Theme                              	Description
Compensation	                      Salary, benefits dissatisfaction
Manager	                            Issues with leadership or reporting manager
Growth	                            Lack of career progression
Work-Life Balance	                  Long hours, stress
Culture	                            Toxic work environment, team issues

# Key Insights
1) Compensation emerged as the most frequent reason for attrition
2) Employees often mentioned lack of career growth opportunities
3) Manager-related issues were strongly linked with poor team culture
4) Early-tenure employees (<1 year) frequently cited work-life imbalance

