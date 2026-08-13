<div align="center">

# 👥 HR Analytics Dashboard

### 📊 Employee Attrition & Workforce Analysis

**An interactive HR analytics project built using Power BI, Tableau, SQL and Excel.**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Analysis-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

**Power BI • Tableau • SQL • Excel • DAX • Data Visualization**

</div>

---

## 📌 Project Overview

The **HR Analytics Dashboard** is an end-to-end data analytics and Business Intelligence project focused on analyzing employee attrition, workforce demographics, departmental trends, and job satisfaction.

The project uses **SQL for data analysis** and presents the results through **two interactive dashboards — Power BI and Tableau**.

---

## 🎯 Project Objectives

- 👥 Analyze total employee count and active employees
- 🚪 Analyze employee attrition and attrition rate
- 👤 Compare attrition across genders
- 🏢 Analyze department-wise attrition
- 🎓 Analyze attrition across education fields
- 🎂 Analyze attrition across age groups
- ⭐ Analyze job satisfaction by job role
- 📊 Present HR insights using Power BI and Tableau

---

## 📊 Project at a Glance

| Category | Details |
|---|---|
| 🎯 Project Type | HR Analytics |
| 📊 BI Tools | Power BI & Tableau |
| 🗄️ Data Analysis | SQL / PostgreSQL |
| 📂 Dataset | HR Employee Dataset |
| 🧹 Data Preparation | Excel / Data Transformation |
| 📐 Calculations | DAX & Calculated Fields |
| 📈 Visualization | Interactive Dashboards |
| 💡 Focus | Employee Attrition & Workforce Analysis |

---

# 📸 Dashboard Preview

## 🟨 Power BI Dashboard

<div align="center">

<img src="Power%20BI%20Dashboard/powerbi-dashboard.png" width="95%">

</div>

### Power BI Analysis

- 📊 Employee KPIs
- 🚪 Attrition analysis
- 📉 Attrition rate
- 👥 Workforce demographics
- 🏢 Department-wise analysis
- 👤 Gender-wise attrition
- 🎓 Education-field analysis
- 🎂 Age-group analysis
- ⭐ Job satisfaction

---

## 🟧 Tableau Dashboard

<div align="center">

<img src="Tableau%20Dashboard/tableau-dashboard.png" width="95%">

</div>

### Tableau Analysis

- 👥 Employee demographics
- 🚪 Attrition analysis
- 🏢 Department analysis
- 👤 Gender analysis
- 🎓 Education-field analysis
- 🎂 Age-group analysis
- ⭐ Job satisfaction
- 🎛️ Interactive filtering

---

# 🔄 Data Analytics Workflow

```text
                    📂 HR DATASET
                         │
                         ▼
                  🧹 DATA PREPARATION
                         │
                         ▼
                    🗄️ SQL ANALYSIS
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
        🟨 POWER BI             🟧 TABLEAU
              │                     │
              ▼                     ▼
          DAX / MODELING      CALCULATED FIELDS
              │                     │
              └──────────┬──────────┘
                         ▼
                  📊 VISUALIZATION
                         │
                         ▼
                   💡 HR INSIGHTS
```

---

# 📈 Key HR Metrics

| KPI | Description |
|---|---|
| 👥 **Employee Count** | Total number of employees |
| 🚪 **Attrition Count** | Number of employees who left |
| 📉 **Attrition Rate** | Percentage of employees who left |
| ✅ **Active Employees** | Employees remaining in the organization |
| 🎂 **Average Age** | Average age of employees |

---

# 🔍 HR Analysis

### 👥 Employee Analysis

- Employee count
- Age distribution
- Gender distribution
- Department distribution
- Employee demographics

### 🚪 Attrition Analysis

- Overall attrition count
- Overall attrition rate
- Gender-wise attrition
- Department-wise attrition
- Education-field-wise attrition
- Age-group-wise attrition

### ⭐ Job Satisfaction Analysis

- Job role
- Satisfaction rating
- Number of employees
- Satisfaction distribution

---

# 🗄️ SQL Analysis

SQL was used to perform analytical queries on the HR dataset.

### Key Analysis

```text
📊 Employee Count
        ↓
🚪 Attrition Count
        ↓
📉 Attrition Rate
        ↓
✅ Active Employees
        ↓
🎂 Average Age
        ↓
👤 Gender-wise Attrition
        ↓
🏢 Department-wise Attrition
        ↓
🎓 Education Field-wise Attrition
        ↓
🎂 Age Band Analysis
        ↓
⭐ Job Satisfaction Analysis
```

### SQL Concepts Used

- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- Aggregate Functions
- `CASE`
- Subqueries
- `CAST`
- PostgreSQL `CROSSTAB`

---

# 🧮 Example SQL Queries

### Employee Count

```sql
SELECT SUM(employee_count) AS employee_count
FROM hrdata;
```

### Attrition Count

```sql
SELECT COUNT(attrition)
FROM hrdata
WHERE attrition = 'Yes';
```

### Average Employee Age

```sql
SELECT ROUND(AVG(age), 0) AS average_age
FROM hrdata;
```

> Additional SQL queries are available in the `SQL` folder.

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🟨 **Power BI** | Interactive dashboard & data visualization |
| 🟧 **Tableau** | Interactive dashboard & visualization |
| 🗄️ **SQL / PostgreSQL** | Data analysis & analytical queries |
| 🟩 **Microsoft Excel** | Dataset & data preparation |
| 📐 **DAX** | Power BI calculations |
| 📊 **Calculated Fields** | Tableau calculations |

---

# ✨ Dashboard Features

| Feature | Power BI | Tableau |
|---|:---:|:---:|
| 📊 KPI Analysis | ✅ | ✅ |
| 🎛️ Interactive Filters | ✅ | ✅ |
| 📈 Data Visualization | ✅ | ✅ |
| 👥 Employee Analysis | ✅ | ✅ |
| 🚪 Attrition Analysis | ✅ | ✅ |
| 🏢 Department Analysis | ✅ | ✅ |
| 👤 Gender Analysis | ✅ | ✅ |
| 🎓 Education Analysis | ✅ | ✅ |
| 🎂 Age Analysis | ✅ | ✅ |
| ⭐ Job Satisfaction | ✅ | ✅ |

---

# 📊 Power BI vs Tableau

| Area | Power BI | Tableau |
|---|---|---|
| Dashboard | Interactive | Interactive |
| Calculations | DAX | Calculated Fields |
| Filters | Slicers / Filters | Filters |
| Visualization | Power BI Visuals | Tableau Visuals |
| Data Modeling | Power BI Model | Tableau Data Model |

---

# 💡 Key Insights

The analysis enables identification of:

- 🏢 Departments with higher employee attrition
- 👤 Differences in attrition across genders
- 🎂 Attrition patterns across age groups
- 🎓 Attrition across education fields
- ⭐ Differences in job satisfaction by job role
- 👥 Overall workforce composition
- 📉 Overall employee attrition patterns

> Numerical findings should be taken directly from the final dashboards.

---

# 🎓 Skills Demonstrated

### 📊 Data Analytics
- Exploratory Data Analysis
- KPI Development
- Business Question Analysis
- Insight Generation
- Data Storytelling

### 🗄️ SQL
- Data Filtering
- Aggregation
- Grouping
- Sorting
- Conditional Analysis
- Subqueries
- PostgreSQL Crosstab

### 🟨 Power BI
- Dashboard Design
- Data Modeling
- DAX
- Interactive Visualizations
- KPI Cards
- Filters / Slicers

### 🟧 Tableau
- Dashboard Design
- Calculated Fields
- Interactive Filters
- Data Visualization
- Data Storytelling

### 🟩 Excel
- Data Handling
- Data Preparation
- Dataset Management

---

# 📁 Repository Structure

```text
HR-Analytics-Dashboard/
│
├── 📊 Power BI Dashboard/
│   ├── HR Analytics Dashboard.pbix
│   └── powerbi-dashboard.png
│
├── 📈 Tableau Dashboard/
│   ├── HR Analytics Dashboard.twbx
│   └── tableau-dashboard.png
│
├── 📂 Dataset/
│   └── HR Data.xlsx
│
├── 🗄️ SQL/
│   └── HR Analytics Queries.sql
│
├── 📄 Documentation/
│   └── HR Analytics Project Report.pdf
│
└── 📘 README.md
```

---

# ▶️ How to Explore the Project

### 🟨 Power BI

1. Download the `.pbix` file.
2. Open it using **Microsoft Power BI Desktop**.
3. Explore the dashboard using filters and visuals.

### 🟧 Tableau

1. Download the `.twbx` file.
2. Open it using **Tableau Desktop**.
3. Explore the interactive dashboard.

### 🗄️ SQL

Open the SQL file to review the analytical queries used in the project.

---

# 📚 Project Documentation

Detailed project documentation is available in:

```text
Documentation/
└── HR Analytics Project Report.pdf
```

---

# 🚀 Future Enhancements

- ☁️ Publish dashboards to Power BI Service
- 🌐 Publish Tableau dashboard online
- 📱 Create mobile-friendly dashboard layouts
- 🔄 Automate data refresh
- 📈 Add advanced HR trend analysis
- 🤖 Add predictive attrition analysis
- 🔐 Implement role-based dashboard access

---

# 📚 What I Learned

Through this project, I strengthened my ability to:

- Analyze HR data
- Write SQL queries for business questions
- Calculate HR KPIs
- Build Power BI dashboards
- Build Tableau dashboards
- Create interactive visualizations
- Compare two BI platforms
- Communicate analytical findings through data storytelling

---

# 👩‍💻 Author

<div align="center">

## Sakshi Dhumane

### Aspiring Data Analyst

**SQL | Power BI | Tableau | Excel | Data Analytics**

[![GitHub](https://img.shields.io/badge/GitHub-sakshidhumane-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sakshidhumane)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)

</div>

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

**Built with Power BI • Tableau • SQL • Excel**

</div>
