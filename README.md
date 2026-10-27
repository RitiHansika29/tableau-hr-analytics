# HR Analytics: Employee Attrition Dashboard (Tableau)

An interactive two-page Tableau dashboard that shows who leaves a company, and which departments, roles and employee groups are most at risk.

**Live dashboard:** [PASTE YOUR TABLEAU PUBLIC LINK HERE]

![Overview dashboard](screenshots/dashboard-1-overview.png)
![Deep dive dashboard](screenshots/dashboard-2-deep-dive.png)

## Problem Statement

Employee attrition is costly: hiring, onboarding and lost productivity add up quickly. This project answers three business questions for an HR team:

1. How big is the attrition problem overall?
2. Which departments, roles and employee groups lose people fastest?
3. Which factors (such as overtime, age and marital status) are linked to leaving, and what can HR do about it?

## Dataset

- **Source:** Kaggle, HR Employee Attrition dataset (`WA_Fn-UseC_-HR-Employee-Attrition.csv`)
- **Size:** 1,470 employee records
- **Target field:** `Attrition` (Yes / No)

## Tools

- Tableau Public (calculated fields, bins, KPI cards, dashboard layout)
- CSV dataset from Kaggle

## What Is in the Dashboards

**Dashboard 1: Overview**
- KPI cards: total employees, attrition count, attrition rate, average monthly income
- Attrition rate by department
- Attrition rate by age group
- Attrition rate by job role

**Dashboard 2: Deep Dive**
- Attrition rate by marital status
- Attrition rate by gender
- Attrition rate by overtime

## Key Insights

| Finding | Number |
|---|---|
| Overall attrition rate | 16.1% (237 of 1,470 employees) |
| Highest-risk department | Sales at 20.6%, then Human Resources at 19.0%, then Research & Development at 13.8% |
| Highest-risk job role | Sales Representative at 39.8% |
| Overtime effect | 30.5% attrition with overtime vs 10.4% without (about 3x) |
| Marital status | Single 25.5%, Married 12.5%, Divorced 10.1% |
| Gender | Male 17.0%, Female 14.8% |
| Age | Employees in their 20s leave at 26.2%, falling to 14.3% in their 30s and 9.7% in their 40s |

Note: the youngest age band (under 20) shows a very high rate, but it contains very few employees, so it should be read with caution.

## Recommendations

1. **Limit overtime in high-risk roles.** Overtime is the strongest driver in this data, so workload planning is the quickest lever.
2. **Review pay and career growth for Sales Representatives,** the role with the highest attrition.
3. **Improve onboarding and early-career support** for employees in their 20s, who leave most often.

## Skills Demonstrated

- Defining business questions and turning them into charts
- Calculated fields (attrition rate and attrition count)
- Age binning and sorting
- Choosing the right chart type (bar charts for category rates)
- KPI cards and multi-page dashboard design
- Publishing and sharing on Tableau Public

## Repository Structure

```
.
├── README.md
├── data/         # dataset (or a link to the Kaggle page)
├── screenshots/  # dashboard images
└── workbook/     # Tableau workbook (.twbx), if downloaded
```

Other projects: data/AI-enabled business analytics with KNIME and Power BI (see my GitHub profile).
