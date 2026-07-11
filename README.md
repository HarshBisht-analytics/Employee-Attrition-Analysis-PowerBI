# Employee Attrition Analysis Dashboard | Power BI

## Overview

This project presents an interactive HR Analytics dashboard built in Power BI to analyze employee attrition. The dashboard helps identify workforce trends, high-risk employee segments, and factors associated with employee turnover using descriptive analytics.

---

## Problem Statement

Organizations often experience employee turnover but lack visibility into the factors associated with attrition. HR teams need an interactive dashboard to answer questions such as:

- Which departments have the highest attrition?
- Which job roles are most affected?
- Does salary influence attrition?
- Are new employees leaving more frequently?
- Which work-related factors are associated with higher attrition?

This dashboard provides descriptive insights to support HR decision-making and employee retention strategies.

---

## Objectives

- Analyze employee attrition trends
- Identify high-risk departments and job roles
- Compare attrition across salary and experience groups
- Analyze demographic patterns
- Evaluate work-related factors associated with attrition
- Provide actionable HR recommendations

---

## Dashboard Pages

### Page 1 – Employee Attrition Overview

Provides an overall view of workforce attrition through KPIs and summary visuals.

**KPIs**
- Total Employees
- Employees Left
- Active Employees
- Attrition Rate
- Average Monthly Income

---

### Page 2 – Department & Job Role Analysis

Analyzes attrition across departments and job roles.

Key questions answered:

- Which department has the highest attrition?
- Which job role has the highest attrition risk?
- Which department should HR prioritize?

---

### Page 3 – Salary, Experience & Tenure Analysis

Analyzes how salary, experience, and years at the company are associated with employee attrition.

Focus Areas:

- Salary vs Attrition
- Experience vs Attrition
- Tenure vs Attrition
- High-Risk Employee Segment

---

### Page 4 – Work Factors & Retention Insights

Evaluates workplace factors related to employee attrition.

Analyzed Factors:

- Overtime
- Work-Life Balance
- Job Satisfaction
- Environment Satisfaction
- Business Travel
- Distance From Home
- Job Involvement

---

## Dashboard Preview

### Employee Attrition Overview

<img width="1022" height="575" alt="Screenshot 2026-07-11 221606" src="https://github.com/user-attachments/assets/26b10436-4a9c-4775-88e4-45115866177e" />

---

### Department & Job Role Analysis

<img width="1025" height="575" alt="Screenshot 2026-07-11 221628" src="https://github.com/user-attachments/assets/038709e7-2f37-41ca-886b-16f7ae7c5d88" />

---

### Salary, Experience & Tenure

<img width="1023" height="570" alt="Screenshot 2026-07-11 221655" src="https://github.com/user-attachments/assets/4c3c0e30-f86b-4601-a7bc-6df1e951670c" />

---

### Work Factors & Retention Insights

<img width="1022" height="575" alt="Screenshot 2026-07-11 221709" src="https://github.com/user-attachments/assets/d6a95ce9-221f-412d-9602-465c81b6f92c" />

---

## Tools Used

- Power BI
- Power Query
- DAX
- Microsoft Excel

---

## Data Preparation

The following preprocessing steps were performed:

- Checked missing values
- Verified data types
- Created calculated columns
- Created Age Groups
- Created Salary Groups
- Created Experience Groups
- Created Tenure Groups
- Created Distance Groups
- Created DAX Measures

---

## Key DAX Measures

- Total Employees
- Employees Left
- Active Employees
- Attrition Rate
- Average Monthly Income
- Income Gap

---

## Key Insights

- Overall attrition rate is **16.12%**.
- Sales has the highest department-wise attrition rate.
- Sales Representative has the highest job role attrition rate.
- Low-income employees show higher attrition.
- Employees with 0–5 years of experience are more likely to leave.
- Employees with 0–4 years at the company have higher attrition.
- Overtime employees have significantly higher attrition.
- Poor work-life balance and low job involvement are associated with higher attrition.

---

## Recommendations

- Improve retention strategies for Sales.
- Strengthen onboarding for new employees.
- Review compensation for lower-income employees.
- Reduce excessive overtime.
- Improve employee engagement and work-life balance.
- Conduct regular employee satisfaction surveys.

---

## Repository Structure

```
Employee-Attrition-Analysis-PowerBI
│
├── README.md
├── Employee Attrition Dashboard.pbix
├── Employee_Attrition_Dataset.xlsx
├── Employee Attrition Report.pdf
├── dashboard-images
│   ├── Overview.png
│   ├── Department.png
│   ├── Salary.png
│   └── WorkFactors.png
└── LICENSE
```

---

## Dataset

This project uses the IBM HR Analytics Employee Attrition dataset obtained from Kaggle.

Please refer to the original dataset source for licensing information.

---

## Author

Harsh Bisht

MBA (Business Analytics)

GitHub: https://github.com/bishtharsh029
LinkedIn: www.linkedin.com/in/harsh-29-bisht

---
