# Google Advanced Data Analytics Capstone Project: 
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

### Data dictionary 

- Dataset: *HR_capstone_dataset.csv*
- 14,999 rows – each row is a different employee’s self-reported information
- 10 columns of self-reported information from employees

| Column name | Type | Description |
| ------- | ------- | ------- |
| satisfaction_level | int64 | The employee’s self-reported satisfaction level [0-1] |

