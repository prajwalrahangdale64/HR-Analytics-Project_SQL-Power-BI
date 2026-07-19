# HR Analytics Project (SQL + Power BI)

An end-to-end HR Analytics project that uses PostgreSQL for database creation, data cleaning, and exploratory data analysis (EDA), followed by Power BI for interactive dashboard development and business insights.

The project analyzes over **22,000 employee records** to provide insights into workforce demographics, employee distribution, hiring trends, employee tenure, department performance, turnover, and job roles.

---

# Project Overview

This project follows the complete data analytics workflow:

- Import the HR dataset
- Create the database and tables
- Clean and prepare the data using PostgreSQL
- Perform Exploratory Data Analysis (EDA) using SQL queries
- Export SQL query results
- Build an interactive Power BI dashboard
- Generate business insights

---

# Tools & Technologies

- PostgreSQL
- Power BI Desktop
- Jupyter Notebook
- CSV Dataset

---

# Dataset

- HR Employee Dataset
- 22,000+ employee records
- Time Period: 2000 – 2020

---

# Business Questions

1. What is the average employee tenure?
2. What is the gender distribution of employees?
3. How many employees work at headquarters versus remotely?
4. How has employee hiring changed over the years? (Hiring Cohort Analysis)
5. How are employees distributed across different states/city?
6. What is the race/ethnicity distribution of employees?
7. What is the age distribution of employees?
8. How does age distribution vary by gender?
9. How does gender distribution vary across departments?
10. Which departments have the highest turnover rates?
11. What is the average employee tenure for each department?
12. What is the distribution of job titles?
13. How does gender distribution vary across job titles?

---

# Key Findings

- The average employee tenure is **7.91 years**.
- Male employees slightly outnumber female employees.
- Approximately **75%** of employees work at headquarters, while **25%** work remotely.
- The active employee percentage has shown an overall upward trend over the years.
- Ohio has the highest number of employees among all states.
- White employees form the largest ethnic group in the company.
- Most employees belong to the 30–39 age group, followed closely by employees in their 40s and 50s.
- Gender distribution across departments is generally balanced, with Engineering having the highest employee count.
- Department turnover rates range from approximately **11%–19%**, with Auditing showing the highest turnover.
- Average employee tenure across departments is fairly consistent, ranging from **8–9 years**.
- Research Assistant II is the most common job role in the company.

---

# Project Structure

```text
HR-Analytics-Project_SQL-Power-BI/
│
├── 0. HR Dataset/
│   └── Human Resources.csv
│
├── 1. HR Database Creation - SQL.ipynb
│
├── 2. HR Data Cleaning - SQL.ipynb
│
├── 3. HR EDA - SQL.ipynb
│
├── 4. SQL EDA Exports/
│   ├── age_distribution.csv
│   ├── age_distribution_by_gender.csv
│   ├── average_employee_tenure_by_department.csv
│   ├── average_terminated_employee_tenure.csv
│   ├── department_gender_distribution.csv
│   ├── department_turnover_rate.csv
│   ├── employee_distribution_by_state.csv
│   ├── ethnicity_distribution.csv
│   ├── gender_distribution.csv
│   ├── hiring_cohort_analysis.csv
│   ├── job_title_distribution.csv
│   ├── job_title_gender_distribution.csv
│   └── work_location_distribution.csv
│
├── 5. HR Analytics Dashboard.pbix
│
├── 6. HR Analytics Dashboard.pdf
│
└── 7. Dashboard Screenshots/
    ├── 1. Executive Summary.PNG
    ├── 2. Geographic Analysis.PNG
    ├── 3. Demographic Analysis.PNG
    ├── 4. Department Analysis.PNG
    └── 5. Job Role Analysis.PNG
```

---

# Author

**Prajwal Rahangdale**
