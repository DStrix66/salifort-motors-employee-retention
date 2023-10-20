# **Salifort Motors Customer Churn**

*2-13 September 2023*

Salifort Motors suffers from high employee turnover, which costs the company resources in interviewing, hiring, and onboarding new employees at a higher-than-industry rate. To develop an effective retention strategy, the HR department commissioned me to analyse their data set on employee churn to gain insight into factors affecting employee turnover.

**Goals**: Support decision-making for developing an employee retention strategy by (i) identifying key factors affecting employees leaving the company and (ii) constructing a model that accurately predicts which individual employees are likely to leave the company.

**Result**: The goals were successfully achieved: (i) Key factors affecting employees leaving the company are satisfaction level, time at the company, and workload, and (ii) a model was developed with a 93% success rate in identifying employees at risk of leaving the company. Additional insights useful for developing a retention strategy were also extracted.

## **PROJECT SUMMARY**

An EDA was conducted to clean and prepare the data set for predictive modelling. Features were extracted and selected iteratively in parallel with testing various binomial classification ML models, namely logistic regression, naïve Bayes, decision-tree, and tree-based gradient boosting machine. The latter two models were highly successful at predicting employee turnover with similar performance metrics (a precision of 97% and a recall of 92-93%). Both models identified the same factors as impacting employees leaving the company, namely satisfaction, time at the company, and workload. 

## **FINDINGS**

These factors (satisfaction, time at the company, and workload) do not have simple linear relationships to turnover. For example, employees within certain high and low satisfaction intervals were both more likely to leave. Thus, further investigation is required to determine the nature of the impact these factors have on employees leaving. This would be informative for developing a nuanced and effective employee retention strategy.

Additional findings useful to the goal that were not part of the initial project plan were also identified, mostly with regards to employee management. For instance, there doesn’t appear to be a clear process for promoting high-performing employees, or for developing capacity in struggling employees.
