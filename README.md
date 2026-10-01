📊 HR Analytics — Executive Workforce & People Analytics Suite

An end-to-end **HR Analytics project** designed to analyze workforce, attrition, recruitment, performance, compensation, employee engagement, absenteeism, and compliance data.

The project combines **Python analytics, Excel dashboarding, data cleaning, KPI analysis, visualization, and business insights** to transform raw HR data into decision-support information for HR and business stakeholders.

---

## 🎯 Project Objective

The objective of this project is to understand workforce performance and identify important HR trends using multiple related HR datasets.

The analysis follows an end-to-end analytical process:

**Business Problem → Data Understanding → Data Preparation → KPI Definition → Data Analysis → Visualization → Insights → Business Recommendations**

---

## 🏢 Business Areas Covered

The project covers eight major HR analytics areas:

1. **Workforce Planning**
2. **Attrition & Retention Diagnostics**
3. **Talent Acquisition & Recruitment Funnel**
4. **Performance, Rewards & Compensation Parity**
5. **Employee Engagement & Exit Sentiment**
6. **Absenteeism & Early Warning Analysis**
7. **Statutory & Compliance Audit**
8. **Executive Balanced Scorecard**

---

## 📁 Dataset

The project uses 10 related HR datasets:

| Dataset                              | Description                                |
| ------------------------------------ | ------------------------------------------ |
| `01_departments.csv`                 | Department information                     |
| `02_employees.csv`                   | Employee master data                       |
| `03_attrition_exits.csv`             | Employee exit and attrition information    |
| `04_exit_reviews_raw.csv`            | Exit interview/review information          |
| `05_performance.csv`                 | Employee performance records               |
| `06_engagement_survey.csv`           | Employee engagement survey data            |
| `07_compliance_trainings.csv`        | Mandatory training records                 |
| `08_compliance_employee_records.csv` | Employee compliance records                |
| `09_attendance_leave.csv`            | Attendance, leave and overtime information |
| `10_recruitment.csv`                 | Recruitment and hiring information         |

The datasets are connected through employee and department-level relationships to support cross-functional HR analysis.

---

# 🔄 Analytical Process

## 1. Business Understanding

The first step is to identify the HR/business questions that need to be answered.

Examples:

* What is the current workforce size?
* Which departments have headcount gaps?
* What is the employee attrition rate?
* What factors are associated with employee exits?
* Which recruitment sources perform better?
* How does performance relate to compensation?
* What is the employee engagement level?
* Are absenteeism patterns changing before employee exits?
* Are mandatory compliance requirements being completed?
* Which departments require management attention?

---

## 2. Data Understanding

The project contains multiple relational HR tables covering:

* Employees
* Departments
* Attrition
* Recruitment
* Performance
* Compensation
* Engagement
* Exit reviews
* Attendance
* Leave
* Overtime
* Compliance training
* Statutory records

The data is inspected before analysis to understand its structure, columns, relationships, and business meaning.

---

## 3. Data Preparation & Engineering

The analysis includes data preparation and aggregation before calculating business metrics.

Key activities include:

* Loading multiple CSV datasets
* Date parsing
* Data type handling
* Filtering active and exited employees
* Joining related HR tables
* Grouping data by department and other dimensions
* Aggregating employee-level information
* Creating analytical metrics
* Preparing datasets for visualization

---

# 📈 HR Analytics Reports

## 1. Workforce Planning

Analyzes the organization's workforce structure and capacity.

### Key Metrics

* Active Headcount
* Headcount Target
* Headcount Variance
* Target Fulfillment %
* Total Payroll
* Budget Utilization
* Average Compensation
* Span of Control
* Work Mode Distribution

### Visualizations

* Headcount Target vs Actual
* Budget Allocation vs Actual Payroll
* Organizational Level Distribution
* Work Mode Distribution

---

## 2. Attrition & Retention Diagnostics

Analyzes employee exits and potential attrition drivers.

### Key Metrics

* Overall Attrition Rate
* Voluntary Attrition
* Involuntary Attrition
* Regrettable Attrition
* Early Attrition
* Attrition by Department
* Exit Reasons
* Commute Distance
* Overtime Status

### Visualizations

* Department Attrition
* Exit Reason Analysis
* Behavioral/Working Condition Drivers
* Commute Distance Analysis

---

## 3. Talent Acquisition & Recruitment Funnel

Evaluates recruitment efficiency and hiring performance.

### Key Metrics

* Time-to-Hire
* Offer-to-Join Time
* Recruitment Funnel Yield
* Recruitment Source Performance
* Hiring Cost
* Quality of Hire
* Early Turnover by Recruitment Source

### Visualizations

* Hiring Time and Cost by Source
* Recruitment Funnel
* Early Turnover by Recruitment Source

---

## 4. Performance, Rewards & Compensation Parity

Analyzes employee performance, compensation and development.

### Key Metrics

* Performance Rating
* Compensation
* Salary/Hike Analysis
* Gender Pay Gap
* Pay-for-Performance Relationship
* Training Hours
* Performance Improvement

### Visualizations

* Performance Rating Distribution
* Performance vs Salary Hike
* Compensation by Level/Gender
* Training Hours vs Performance

---

## 5. Employee Engagement & Exit Sentiment

Analyzes employee engagement and exit-review sentiment.

### Key Metrics

* Employee Engagement
* eNPS
* Promoters
* Passives
* Detractors
* Exit Review Sentiment
* Positive Sentiment
* Negative Sentiment
* Mixed Sentiment

### Visualizations

* eNPS Distribution
* Engagement Pillar Analysis
* Exit Review Sentiment Analysis

---

## 6. Absenteeism & Early Warning Analysis

Analyzes attendance, absence and overtime patterns to identify potential early warning signals.

### Key Metrics

* Absenteeism Rate
* Unplanned Absence
* Overtime
* Pre-Exit Absenteeism
* Monthly Absence Trend

### Visualizations

* Monthly Absenteeism & Overtime Trend
* Pre-Exit Absence Trajectory

---

## 7. Compliance Audit

Evaluates employee compliance and mandatory training completion.

### Key Metrics

* Training Completion Rate
* Overdue Training
* Mandatory Training Status
* PF/UAN Linkage
* NDA Completion
* Background Verification Status
* Compliance Records

### Visualizations

* Training Completion by Course
* Statutory/Legal Compliance Status

---

## 8. Executive Balanced Scorecard

Combines multiple HR dimensions into a single management view.

The scorecard brings together:

* Workforce
* Recruitment
* Attrition
* Absenteeism
* Engagement
* Performance
* Compliance
* Department-level HR health

This provides an executive-level view of departmental workforce performance.

---

# 🛠️ Tools & Technologies

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### Microsoft Excel

* Data Cleaning
* Formulas
* Pivot Tables
* Charts
* KPI Cards
* Dashboard Design
* Conditional Formatting
* Interactive Navigation

### Other

* GitHub
* AI-assisted analytics workflow

---

# 📊 Dashboard

The project includes an **Executive HR Analytics Dashboard** designed based on an executive HR intelligence layout.

### Dashboard Features

* Executive KPI cards
* Workforce planning
* Attrition diagnostics
* Recruitment funnel
* Rewards & compensation analysis
* Employee engagement
* Absenteeism warning analysis
* Compliance audit
* Balanced scorecard
* 25 analytical charts
* Department-level analysis
* Navigation between analytical views

The Excel dashboard is designed to provide a consolidated view of HR performance while allowing users to navigate into specific analytical areas.

---

# 📓 Jupyter Notebook

The Jupyter Notebook documents the complete analytical workflow.

Each report follows:

**Business Objective → Metric Definition → Data Engineering → Analysis → Visualization → Strategic Insights**

The notebook therefore contains both the **business analytical reasoning** and the **Python implementation used to perform the analysis**.

---

# 💡 Key Analytical Questions

This project answers questions such as:

* How large is the active workforce?
* Where are workforce capacity gaps?
* Which departments experience higher attrition?
* What working conditions are associated with employee exits?
* How efficient are recruitment sources?
* How long does the recruitment process take?
* How does compensation vary across employee groups?
* What is the relationship between performance and compensation?
* What is the employee engagement level?
* What patterns appear in exit reviews?
* Does absenteeism change before employee exits?
* What mandatory training remains incomplete?
* Which departments require greater HR attention?

---

# 📂 Repository Structure

```text
HR-Analytics/
│
├── 01_departments.csv
├── 02_employees.csv
├── 03_attrition_exits.csv
├── 04_exit_reviews_raw.csv
├── 05_performance.csv
├── 06_engagement_survey.csv
├── 07_compliance_trainings.csv
├── 08_compliance_employee_records.csv
├── 09_attendance_leave.csv
├── 10_recruitment.csv
│
├── HR_Analytics_HTML_Matched_Dashboard.xlsx
├── hr_analytics_dashboard.html
├── HR_Analytics.ipynb
│
└── README.md
```

---

# 🚀 How to Use the Project

### Python Analysis

Open the Jupyter Notebook:

```text
HR_Analytics.ipynb
```

Run the notebook to follow the complete analytical workflow from data loading through visualization and insights.

### Excel Dashboard

Open:

```text
HR_Analytics_HTML_Matched_Dashboard.xlsx
```

Start with:

```text
HTML_Dashboard
```

Use the navigation sections to explore the different HR analytical views.

---

# 📌 Project Outcome

This project demonstrates how multiple HR datasets can be transformed into an **end-to-end HR analytics solution**.

It combines:

**Data → Analysis → Visualization → Business Insights**

rather than focusing only on individual Python calculations or dashboard charts.

---

## 👤 Author

**Pavithran V**

Business Analytics | Data Analytics | HR Analytics

Skills demonstrated:

`Excel` `SQL` `Python` `Power BI` `Tableau` `Data Cleaning` `Data Visualization` `Business Analytics` `HR Analytics` `AI Tools`

---

## ⭐ Project

If you find this project useful, feel free to explore the repository and review the analytical workflow, dashboard and notebook.
