
# Employee Attrition Analysis

## Problem Statement

Employee attrition leads to increased hiring costs, productivity loss, and operational inefficiencies.

This project analyzes employee data to identify key drivers of attrition and provide actionable insights to improve retention.

## Dashboard Preview  
![Dashboard](images/dashboard_preview.png)

## Objectives

* Identify factors influencing employee attrition
* Segment high-risk employee groups
* Analyze the impact of compensation, overtime, and experience
* Build an interactive Tableau dashboard for decision-making

---

## Dataset Overview

* Total Records: 1470 employees
* Features: 35 columns including demographics, job details, and satisfaction metrics
* Target Variable: Attrition (Yes/No)

### Key Attributes

* Demographics: Age, Gender, Marital Status
* Job Details: Department, Job Role, Job Level
* Compensation: Monthly Income, Salary Hike
* Work Factors: Overtime, Business Travel
* Satisfaction Metrics: Work-Life Balance, Job Satisfaction
* Experience: Years at Company, Total Working Years

---

## Tools and Technologies

* SQL

  * Data cleaning
  * Data transformation
  * Analytical queries

* Excel

  * Data validation
  * Pivot tables for cross-checking

* Tableau

  * Interactive dashboards
  * Data visualization
  * Insight generation

---

## Approach

### Data Cleaning (SQL)

* Checked for null values and duplicates
* Standardized categorical fields
* Created derived metrics for analysis

### Data Analysis (SQL)

* Calculated overall attrition rate
* Performed department-wise and role-wise analysis
* Compared income levels across attrition groups
* Analyzed overtime impact
* Studied experience-based attrition trends

### Data Validation (Excel)

* Created pivot tables for verification
* Cross-validated SQL outputs
* Ensured consistency in aggregates

### Data Visualization (Tableau)

* Built interactive dashboard with filters
* Visualized attrition by department and role
* Compared salary across attrition groups
* Highlighted overtime and experience trends

---

## Key Insights

* Overall attrition rate: 16.12 percent

* Department-level insights

  * Sales has the highest attrition (~21 percent)
  * Indicates role-specific challenges and pressure

* Compensation insights

  * Employees who left earn significantly less on average
  * Suggests income disparity as a key driver

* Overtime impact

  * Employees working overtime are significantly more likely to leave
  * Indicates workload imbalance

* Experience trends

  * High attrition in early-career employees (0–2 years)
  * Noticeable attrition in long-tenure employees (20+ years)

* Travel factor

  * Frequent business travel is linked with higher attrition (~25 percent)

---

## Dashboard

The Tableau dashboard enables:

* Identification of high-risk employee segments
* Department and role-level attrition tracking
* Analysis of compensation and workload factors
* Interactive filtering for deeper insights

### Key Views

* Attrition by Department
* Attrition by Job Role
* Salary vs Attrition
* Overtime Impact
* Experience vs Attrition Trend

---

## Business Impact

* High attrition increases recruitment and training costs
* Productivity loss due to frequent employee turnover
* Increased pressure on remaining employees

### Strategic Value

* Identifies controllable factors like compensation and workload
* Enables targeted retention strategies
* Supports data-driven HR decision-making

---

## Recommendations

* Compensation Optimization

  * Address salary gaps in high-risk roles

* Workload Management

  * Reduce excessive overtime
  * Introduce flexible work policies

* Role-Specific Strategy

  * Improve incentives and support in Sales roles

* Early Career Retention

  * Strengthen onboarding programs
  * Provide mentorship

* Long-Tenure Engagement

  * Offer growth opportunities
  * Recognize contributions

* Travel Flexibility

  * Provide hybrid options or travel benefits

---

## How to Use

* Run SQL queries to perform analysis
* Use Excel for validation and quick summaries
* Open Tableau dashboard file for interactive insights

---

## Conclusion

* Attrition is influenced by compensation, workload, and experience
* High-risk segments can be identified using data analysis
* Targeted interventions can significantly improve retention

---

## Author

Shubhi Yadav
Aspiring Data Analyst
SQL | Excel | Tableau

