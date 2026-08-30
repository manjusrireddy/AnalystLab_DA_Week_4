# HealthConnect Clinic — Data Analytics Track

**AnalystLab Africa Week-04 | Improving Patient Appointment Attendance Using Data and AI**

## Project Overview

HealthConnect Clinic is a fictional healthcare provider facing a significant operational challenge: patients frequently miss scheduled appointments, disrupting clinic efficiency and patient care. This project explores how data analysis can help the clinic understand and reduce missed appointments (no-shows).

**Central Project Question:**
How can HealthConnect Clinic use data and AI to reduce missed appointments and improve the patient support experience?

This repository documents the **Data Analytics track** contribution to the shared, multi-track HealthConnect Experience Lab.

## My Role (Data Analytics Track)

My responsibility is to explore the appointment dataset, assess data quality, define relevant business questions, and propose meaningful KPIs that will guide deeper analysis and dashboard development in later stages of the project.

## Dataset

- **File:** `HealthConnect_Appointment_Data.csv`
- **Records:** 5,000 fictional, anonymised appointment records
- **Fields:** 18 columns covering patient demographics, appointment details, booking history, reminders, and outcomes
- **Reference:** `HealthConnect_Data_Dictionary.xlsx` — full variable definitions and expected value ranges


## Week 4 — Problem Understanding & Initial Analysis

**Status: Complete**

- Reviewed the dataset structure and Data Dictionary
- Conducted a full data quality assessment (missing values, duplicates, data types, logical consistency)
- Confirmed overall **no-show rate of 48.5%**, validating the scale of the business problem
- Defined 6 relevant business questions tied to reducing no-shows
- Proposed 5 KPIs, each linked to a specific business question

**Key finding:** The 27.3% missing values in `reminder_channel` are not a data error — they correspond exactly to appointments where no reminder was sent.

📄 Full write-up: [`docs/initial_analysis_document.docx`](docs/initial_analysis_document.docx)
📄 Week summary: [`docs/week4_project_summary.docx`](docs/week4_project_summary.docx)

## Proposed KPIs

| KPI | Business Question |
|---|---|
| Overall No-Show Rate (%) | What is the scale of the attendance problem? |
| No-Show Rate by Reminder Channel | Do reminders reduce no-shows? |
| No-Show Rate by Appointment Type | Which appointment types are highest-risk? |
| Repeat No-Show Rate | Does prior no-show history predict future behaviour? |
| No-Show Rate by Distance Band | Does distance to the clinic affect attendance? |

## Tools Used

- **Python** (pandas) — data loading and quality assessment
- **Jupyter Notebook** (via VS Code) — analysis environment
- **Power BI Service** — planned for interactive dashboard (upcoming weeks)

## Roadmap

- [x] Week 4 — Problem understanding, data quality assessment, KPI proposal
- [ ] Week 5 — Clean date fields, calculate KPIs, segment analysis
- [ ] Week 6+ — Build interactive Power BI dashboard, business problem investigation, insights & recommendations

## Author

**Manjusri** — MSc Artificial Intelligence (Industrial Placement), University of East London
[LinkedIn](#) | [GitHub](#)

---
*Part of the AnalystLab Africa Data Analytics Internship / Experience Lab programme.*
