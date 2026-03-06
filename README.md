# Recruitment Funnel Performance & Candidate Progress Analysis

## Overview
This project is part of an internship with **Career Catalyst, UAE**, focusing on analyzing the **Recruitment Funnel Performance and Candidate Progress** between **January 2025 and September 2025**.

The objective is to evaluate candidate progression across different hiring stages, measure funnel efficiency, identify drop-off points, and generate insights to improve the recruitment process.

The dashboard provides HR teams with a clear view of candidate movement, recruitment effectiveness, and department-level hiring performance.

---

## Objectives
- Analyze candidate flow through recruitment stages
- Measure **recruitment funnel efficiency**
- Identify **stages with the highest drop-offs**
- Evaluate **best-performing applicant sources**
- Compare **department hiring performance**
- Provide **actionable recommendations** to improve hiring efficiency

---

## Recruitment Funnel Stages
The recruitment process analyzed in this project follows the hiring funnel below:

Applications → Screening → Interviewed → Offered → Hired

Possible outcomes after each stage include:

- **Advanced** – Candidate progressed to the next stage
- **Hired** – Candidate successfully hired
- **Dropped** – Candidate left the recruitment process
- **Rejected** – Candidate was not selected

---

## Dataset Description

The dataset used in this project contains recruitment process data with the following columns:

| Column | Description |
|------|-------------|
| ApplicantID | Unique identifier for each candidate |
| DateOfApplication | Date when the candidate applied |
| Name | Candidate name |
| Department | Department applied for (Engineering, Finance, Marketing, HR, Sales) |
| Source | Application source (Company Website, Indeed, Referral, Job Fair, LinkedIn) |
| Stage | Current stage in recruitment funnel |
| DayInStage | Number of days spent in a stage |
| StatusNextStage | Outcome after the stage (Advanced, Hired, Dropped, Rejected) |

---

## Key Metrics & KPIs

The following metrics were calculated using **DAX in Power BI**:

- **Total Applicants**
- **Total Hires**
- **Total Dropped Candidates**
- **Stage Conversion Rate**
- **Drop-off Rate**
- **Average Days per Stage**
- **Applicants by Source**
- **Applicants by Department**

---

## Dashboard Structure

### Page 1 – Recruitment Funnel Overview
Provides a high-level overview of the hiring pipeline.

Visualizations include:

- KPI Cards (Total Applicants, Total Hires, Total Dropped)
- Recruitment Funnel Visualization
- Stage Conversion Rate by Stage
- Average Days per Stage
- Application Timeline Trend
- Drop-off Analysis

---

### Page 2 – Source & Department Performance
Focuses on recruitment performance across applicant sources and departments.

Visualizations include:

- Applicants by Source
- Applicants by Department
- Hires by Source
- Hires by Department
- Decomposition Tree
- Insight Cards highlighting top sources and departments

---

## Key Metrics & Analysis

The analysis focuses on:

- **Overall Conversion Rate**
- **Stage Conversion Rates**
- **Average Time in Each Stage**
- **Source Effectiveness**
- **Department Hiring Efficiency**
- **Drop-off Analysis**

These metrics help identify **recruitment bottlenecks and improvement opportunities**.

---

## Deliverables

The final project deliverables include:

- **Power BI Dashboard (.pbix)**
- **Interactive Visualizations**
- **Recruitment Funnel Analysis Report**
- **Insights and Recommendations**

---

## Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
