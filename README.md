# Workforce Utilization Analysis – Power BI Dashboard

## Project Overview

This project analyzes workforce utilization to help organizations monitor employee capacity, workload distribution, and project allocation. The dashboard provides insights into how efficiently employees' time is utilized across departments and projects.

The goal is to identify **underutilized employees, overallocated resources, and workload trends** to support better workforce planning and decision-making.

---

## Business Problem

Organizations often struggle to balance employee workload. Some employees may be overallocated while others remain underutilized. Poor workforce planning can lead to reduced productivity, employee burnout, and inefficient project execution.

This dashboard helps answer key business questions:

* Which employees are **overallocated or underutilized**?
* How do **planned hours compare with actual hours**?
* Which departments have **unused capacity**?
* How are **resources distributed across projects**?

---

## Tools & Technologies Used

* **Excel** – Data preparation and cleaning
* **Power BI** – Data visualization and dashboard creation
* **DAX (Data Analysis Expressions)** – Calculated measures and metrics

---

## Dataset Description

The dataset contains information related to employee workforce planning, including:

* Employee details
* Department information
* Project assignments
* Planned work hours
* Actual work hours
* Resource allocation

This data is used to evaluate workforce efficiency and project workload distribution.

---

## Analytics Workflow

The project follows a structured data analysis workflow:

### 1. Data Collection

Workforce planning data containing employee information, project assignments, planned hours, and actual work hours was used for analysis.

### 2. Data Cleaning

The dataset was cleaned and prepared in Excel:
• Removed missing or inconsistent values
• Standardized column formats
• Prepared data for Power BI import

### 3. Data Modeling

Data was loaded into Power BI and organized using a structured data model connecting employee, project, and time tracking information.

### 4. DAX Calculations

Custom measures were created using DAX to calculate key metrics such as:
• Utilization percentage
• Average utilization
• Overallocated employees

### 5. Dashboard Development

Interactive dashboards were created to analyze workforce utilization across departments, projects, and employees.

### 6. Insight Generation

Insights were generated to identify workforce inefficiencies, capacity gaps, and workload imbalances.

---

## Key Dashboard Reports

### 1. Billable Report

Displays employee billable hours and capacity utilization to monitor productivity.

### 2. External Capacity Overview

Shows workforce capacity allocated to external projects.

### 3. Internal Project Follow-Up Report

Tracks internal project workload and resource assignments.

### 4. Over Allocation Report

Identifies employees who are working beyond their capacity.

### 5. Planned vs Actual Time Report

Compares planned work hours with actual time spent on projects.

---

## Key Metrics & DAX Measures

### Utilization Percentage

Utilization % = Actual Hours / Available Hours

### Average Utilization

Average Utilization = Average of employee utilization percentages

### Overallocated Employees

Employees with utilization greater than 100%

These measures help evaluate employee workload and organizational efficiency.

---

## Key Insights

* Some employees exceed **100% workload capacity**, indicating potential overutilization.
* Certain departments have **unused workforce capacity**.
* External projects consume a large portion of employee hours.
* Differences between **planned and actual work hours** highlight inefficiencies in resource planning.

---

## Business Recommendations

* Redistribute tasks from overallocated employees to underutilized teams.
* Improve workforce planning using capacity monitoring.
* Track project workloads regularly to avoid employee burnout.
* Use workforce analytics to support better project allocation decisions.

---

## Dashboard Screenshots

### Billable Report
![Billable Report](Dashboard_Screenshots/Billable%20Report.png)

### Over Allocation Report
![Over Allocation](Dashboard_Screenshots/Over%20Allocation%20Report.png)

### Planned vs Actual Time
![Planned vs Actual](Dashboard_Screenshots/Planned%20vs%20Actual%20Time%20Report.png)

---

## Repository Structure

Workforce-Planning-PowerBI/
│
├── Data/
│   ├── CapacityandLeaves.csv
│   ├── Company.csv
│   ├── Date.csv
│   ├── Department.csv
│   ├── Internal_Project.csv
│   ├── Planned_Hour.csv
│   ├── Projects.csv
│   ├── Resources.csv
│   └── Tasks.csv
│
├── Dashboard/
│   └── Workforce_Planning.pbix
│
├── Dashboard_Screenshots/
│   ├── billable_report.png
│   ├── external_capacity_overview.png
│   ├── internal_project_followup.png
│   ├── over_allocation.png
│   └── planned_vs_actual.png
│
└── README.md


---

## Project Outcome

This dashboard demonstrates how **data analytics and visualization can support workforce planning**, improve productivity monitoring, and assist managers in making data-driven resource allocation decisions.
