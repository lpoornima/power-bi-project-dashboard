# 📊 Project Management Dashboard — Power BI

An interactive Power BI dashboard built to track project budgets, timelines, team workload, and delivery risk across a portfolio of projects.

## 🎯 Overview
This dashboard answers key business questions a project/finance manager would ask:
- What's our total budget vs actual spend?
- Which projects are overdue or at risk?
- How is budget distributed across departments?
- Which project managers are handling the most workload?

## 🛠️ Tools Used
- **Power BI Desktop** — data modeling, DAX, visualization
- **Excel** — source data (Projects, Tasks, Employees tables)
- **DAX** — custom measures for KPIs

## 📁 Data Model
A star schema with 3 related tables:
- **Projects** (fact/dimension) — budget, status, priority, dates
- **Tasks** — linked to Projects via `ProjectID`, tracks hours and task status
- **Employees** — linked to Tasks via `AssignedTo`, tracks roles and departments

## 📐 Key DAX Measures

## 📈 Dashboard Features
- 5 KPI cards: Total Budget, Actual Cost, Cost Variance, Avg % Complete, Overdue Projects
- Status breakdown donut chart
- Budget vs Actual Cost by Department (clustered bar chart)
- Project Manager workload chart
- Overdue projects table with drill-down details
- High Priority + In Progress projects table
- Conditional formatting to flag risk areas
- Cross-filtering across all visuals for interactive exploration

## 📌 How to Use
1. Download `job project.pbix`
2. Open in Power BI Desktop
3. Explore the interactive visuals — click any chart to filter the whole dashboard

## 👤 Author
Built as a portfolio project to demonstrate Power BI, DAX, and data modeling skills for Data Analyst roles.
