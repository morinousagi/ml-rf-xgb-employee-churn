## Develop a model to predict employee departure

### Problem statement 

High rate of turnover among Salifort Motors (multinational vehicle manufacturing corporation) employees, which is costly in the financial sense.

- What we know - employee survey results from HR, see Data dictionary
- What we do not know - what’s driving the turnover

### Stakeholders
Senior management and HR

### Goal
To tackle the problem, stakeholders want to learn about what might be driving the turnover and predict whether an employee will leave the company – to do this, the team aims to develop a ***classification*** model to predict employee departure.

**Target variable, y (categorical)**
- People who left: ‘left’ = 1
- People who stayed: ‘left’ = 0

### Project milestones

1. EDA & data visualisations (includes statistics, data cleaning, ethical considerations)
2. Logistic regression modeling
3. Tree-based modeling - Random forest and XGBoost
4. Summary & recommendations

### Deliverables
1. [Jupyter notebook](https://github.com/morinousagi/ml-rf-xgb-salifort/blob/main/gada-capstone-salifort.ipynb)
2. [Summary report](https://github.com/morinousagi/ml-rf-xgb-salifort/blob/main/salifort-summary-report.pdf)
3. Additional insights presented in [Tableau story](https://public.tableau.com/app/profile/morinousagi/viz/WIP_17669147168610/Story1)

### Data dictionary 

- Dataset: *HR_capstone_dataset.csv*
- 14,999 rows – each row is a different employee’s self-reported information
- 10 columns of self-reported information from employees

| Column name | Type | Description |
| ------- | ------- | ------- |
| satisfaction_level | int64 | The employee’s self-reported satisfaction level [0-1] |
| last_evaluation | int64 | Score of employee's last performance review [0-1] |
| number_project | int64 | Number of projects employee contributes to |
| average_monthly_hours | int64 | Average number of hours employee worked per month |
| time_spend_company | int64 | How long the employee has been with the company (years) |
| work_accident | int64 | Whether or not the employee experienced an accident while at work |
| left | int64 | Whether or not the employee left the company |
| promotion_last_5years | int64 | Whether or not the employee was promoted in the last 5 years |
| department | str | The employee's department |
| salary | str | The employee's salary (low, medium, or high) |
