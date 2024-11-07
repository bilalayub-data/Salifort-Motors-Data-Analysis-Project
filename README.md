### Project Overview

This project analyzes employee data for Salifort Motors, focusing on understanding and predicting employee attrition. By identifying key factors influencing an employee's decision to leave, the analysis aims to help Salifort Motors develop effective retention strategies and enhance employee satisfaction.

### Project Objectives

Perform exploratory data analysis (EDA) on employee data to uncover patterns and trends related to attrition.
Build predictive models to estimate the likelihood of an employee leaving the organization.
Generate insights to inform HR policies aimed at improving employee retention.

### Dataset 

In this [dataset](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv), there are 14,999 rows, 10 columns, and these variables: 

Variable  |Description |
-----|-----| 
satisfaction_level|Employee-reported job satisfaction level [0&ndash;1]|
last_evaluation|Score of employee's last performance review [0&ndash;1]|
number_project|Number of projects employee contributes to|
average_monthly_hours|Average number of hours employee worked per month|
time_spend_company|How long the employee has been with the company (years)
Work_accident|Whether or not the employee experienced an accident while at work
left|Whether or not the employee left the company
promotion_last_5years|Whether or not the employee was promoted in the last 5 years
Department|The employee's department
salary|The employee's salary (U.S. dollars)

### Model Test Dataset Evaluation Results 

Model|Precision|Recall|F1-Score|Accuracy|
-----|-----|-----|-----|-----|
Logistic|Regression|	80%|83%|80%|83%|			
Random Forest|	87%|	90.40%|88.70%|96.20%|






