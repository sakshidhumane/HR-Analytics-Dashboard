# 👥 HR Analytics Dashboard
### Employee Attrition & Workforce Analysis

An end-to-end **HR Analytics and Business Intelligence project** built using **SQL, Excel, Power BI, and Tableau** to analyze employee attrition, workforce demographics, job roles, salary patterns, and job satisfaction.

The project transforms HR data into interactive dashboards and business insights that can help identify employee retention risks and workforce trends.

---

## 📌 Project Overview

Employee attrition is an important HR challenge that can increase recruitment costs and affect workforce productivity.

This project analyzes employee data to understand:

- Employee attrition and attrition rate
- Department-wise attrition
- Gender-wise attrition
- Age-group attrition
- Education-field attrition
- Job-role distribution
- Job satisfaction
- Salary and workforce patterns
- Employee demographics

The analysis was performed using **SQL**, while **Power BI and Tableau** were used to create interactive dashboards for data visualization and business reporting.

---

## 🎯 Business Questions

This project answers the following HR business questions:

1. What is the overall employee attrition rate?
2. Which departments have the highest attrition?
3. Which job roles experience the highest employee turnover?
4. Which age groups are most affected by attrition?
5. Does job satisfaction appear to be related to employee attrition?
6. How does attrition differ by gender?
7. Which education fields have higher attrition?
8. Which employee groups should HR prioritize for retention?
9. What workforce patterns can be identified from employee demographics?
10. What areas could HR focus on to improve employee retention?

---

# 📊 Dashboard Preview

## 🟨 Power BI Dashboard

![Power BI HR Analytics Dashboard](screenshots/PowerBI%20Dashboard.png)

### Power BI Features

- KPI cards
- Employee and attrition analysis
- Department-wise analysis
- Gender-wise analysis
- Age-group analysis
- Education-field analysis
- Job-role analysis
- Job satisfaction analysis
- Interactive slicers and filters
- DAX-based calculations

---

## 🟧 Tableau Dashboard

![Tableau HR Analytics Dashboard](screenshots/Tableau%20Dashboard.png)

### Tableau Features

- Interactive dashboard
- Employee demographics
- Attrition analysis
- Department analysis
- Gender analysis
- Age-group analysis
- Education analysis
- Job-role analysis
- Job satisfaction analysis
- Interactive filters
- Calculated fields

---

# 📈 Key HR KPIs

| KPI | Value |
|---|---:|
| 👥 Total Employees | 1,470 |
| 🚪 Attrition Count | 237 |
| 📉 Attrition Rate | 16.1% |
| ✅ Active Employees | 1,233 |
| 🎂 Average Age | 37 |

> **Note:** KPI values should match the final Power BI/Tableau dashboards.

---

# 💡 Key Business Insights

### 1. Department Attrition

The **Sales department** has a higher attrition rate compared with Research & Development, indicating a potential employee-retention challenge that requires further investigation.

### 2. Overall Attrition

The overall employee attrition rate is approximately **16.1%**, indicating that a meaningful portion of the workforce has exited the organization.

### 3. Age Group

Employees in the **26–35 age group** represent a significant portion of employee attrition, making this group important for targeted retention strategies.

### 4. Job Roles

Certain job roles experience considerably higher attrition than others, suggesting that employee turnover may be influenced by role-specific factors such as workload, career growth, compensation, or job satisfaction.

### 5. Job Satisfaction

Employees with lower job satisfaction ratings show higher attrition patterns, suggesting that employee engagement and workplace satisfaction may be important factors in retention.

### 6. Overtime

Employees working overtime show higher attrition compared with employees who do not work overtime, indicating that workload may be a potential contributor to employee turnover.

> **Note:** Insights should be validated against the final dashboard results before being used for business decisions.

---

# 🎯 Business Recommendations

Based on the analysis, HR teams could consider:

- Investigating retention challenges in high-attrition departments.
- Reviewing workload and overtime patterns among employees.
- Developing targeted retention strategies for high-risk age groups.
- Improving career development and promotion opportunities.
- Reviewing compensation for high-attrition job roles.
- Improving employee engagement and job satisfaction initiatives.
- Regularly monitoring attrition KPIs through HR dashboards.
- Conducting further analysis to identify the key drivers of employee turnover.

---

# 🔄 Data Analytics Workflow

```text
                    HR DATASET
                        │
                        ▼
              DATA PREPARATION
                   Excel
                        │
                        ▼
                  SQL ANALYSIS
                 PostgreSQL
                        │
              ┌─────────┴─────────┐
              ▼                   ▼
          POWER BI             TABLEAU
              │                   │
              ▼                   ▼
        DAX / MODELING     CALCULATED FIELDS
              │                   │
              └─────────┬─────────┘
                        ▼
                 DATA VISUALIZATION
                        │
                        ▼
                  HR INSIGHTS
                        │
                        ▼
              BUSINESS RECOMMENDATIONS
```

---

# 🗄️ SQL Analysis

SQL was used to analyze the HR dataset and answer key business questions.

### SQL Analysis Performed

- Total employee count
- Active employee count
- Attrition count
- Attrition rate
- Average employee age
- Gender-wise attrition
- Department-wise attrition
- Education-field attrition
- Age-band analysis
- Job-role analysis
- Job satisfaction analysis

### SQL Concepts Used

- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- Aggregate Functions
- `CASE`
- Subqueries
- `CAST`
- `ROUND`
- PostgreSQL `CROSSTAB`

---

## 🧮 Example SQL Queries

### Employee Count

```sql
SELECT SUM(employee_count) AS employee_count
FROM hrdata;
```

### Attrition Count

```sql
SELECT COUNT(*) AS attrition_count
FROM hrdata
WHERE attrition = 'Yes';
```

### Average Employee Age

```sql
SELECT ROUND(AVG(age), 0) AS average_age
FROM hrdata;
```

### Department-wise Attrition

```sql
SELECT department,
       COUNT(*) AS attrition_count
FROM hrdata
WHERE attrition = 'Yes'
GROUP BY department
ORDER BY attrition_count DESC;
```

### Gender-wise Attrition

```sql
SELECT gender,
       COUNT(*) AS attrition_count
FROM hrdata
WHERE attrition = 'Yes'
GROUP BY gender
ORDER BY attrition_count DESC;
```

> Additional SQL analysis is available in the `sql` folder.

---

# 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| 🟨 Power BI | Dashboard development and visualization |
| 🟧 Tableau | Interactive visualization |
| 🗄️ PostgreSQL | SQL analysis and business queries |
| 🟩 Excel | Data preparation and dataset management |
| 📐 DAX | Power BI calculations |
| 📊 Calculated Fields | Tableau calculations |

### Skills Demonstrated

`SQL` • `PostgreSQL` • `Power BI` • `DAX` • `Tableau` • `Excel` • `Data Cleaning` • `Data Visualization` • `KPI Development` • `Business Analysis` • `Data Storytelling`

---

# 📁 Repository Structure

```text
HR-Analytics-Dashboard/
│
├── README.md
│
├── data/
│   └── HR Data.xlsx
│
├── powerbi/
│   └── HR Analytics Dashboard.pbix
│
├── tableau/
│   └── HR Analytics Dashboard.twb
│
├── sql/
│   └── queries.docx
│
├── documentation/
│   └── Documentation.docx
│
└── screenshots/
    ├── PowerBI Dashboard.png
    └── Tableau Dashboard.png
```

---

# ▶️ How to Explore the Project

## 🟨 Power BI

1. Download the `.pbix` file from the `powerbi` folder.
2. Open it using **Microsoft Power BI Desktop**.
3. Use slicers and filters to explore the HR analysis.
4. Review KPI cards and visualizations.

## 🟧 Tableau

1. Download the `.twb` file from the `tableau` folder.
2. Open it using **Tableau Desktop**.
3. Explore the interactive dashboard and filters.

## 🗄️ SQL

1. Open the SQL analysis document from the `sql` folder.
2. Review the queries used to analyze employee attrition and workforce trends.
3. Execute the queries in PostgreSQL using the HR dataset.

---

# 📊 Project Outcomes

This project demonstrates the complete analytics workflow:

```text
Raw HR Data
     ↓
Data Preparation
     ↓
SQL Analysis
     ↓
KPI Development
     ↓
Power BI & Tableau Dashboards
     ↓
Business Insights
     ↓
HR Recommendations
```

The project helped transform raw employee data into actionable HR insights related to **attrition, workforce demographics, job roles, and employee satisfaction**.

---

# 🚀 Future Enhancements

- ☁️ Publish dashboards to Power BI Service
- 🌐 Publish Tableau dashboard online
- 📱 Create mobile-friendly dashboard layouts
- 🔄 Automate data refresh
- 📈 Add historical HR trend analysis
- 🤖 Develop predictive employee attrition analysis
- 🔐 Implement role-based dashboard access

---

# 👩‍💻 Author

## Sakshi Dhumane

**Aspiring Data Analyst**

`SQL` • `Power BI` • `Tableau` • `Excel` • `Data Analytics`

### 🔗 LinkedIn

[Connect with me on LinkedIn](https://www.linkedin.com/in/sakshidhumane)

---

⭐ If you found this project useful, consider giving it a star!

**Built with Power BI • Tableau • SQL • Excel**
