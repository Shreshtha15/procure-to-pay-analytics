# Procure-to-Pay Analytics & Process Intelligence

**Project Status: In Progress**

## Overview

This project analyzes procurement process data from the BPI Challenge 2019 event log to investigate purchasing activities, supplier patterns, spending behavior, and potential process inefficiencies.

The goal is to turn raw event-log data into meaningful business insights using Python, SQL, and Power BI.

## Business Objectives

- Analyze procurement spending across suppliers and purchasing categories.
- Understand the sequence and frequency of purchasing activities.
- Investigate process duration, bottlenecks, and potential delays.
- Identify unusual process patterns and opportunities for further investigation.
- Build an interactive dashboard to communicate findings.

## Dataset

The project uses the **BPI Challenge 2019** event log.

The data contains event-level records associated with purchase document items, including timestamps, activity names, vendor identifiers, purchasing document information, spend classifications, and other process attributes.

The raw dataset is not included in this repository. Refer to the original dataset source and its access terms before downloading or redistributing it.

## Tools & Technologies

- **Python:** Data exploration and analysis
- **Pandas & NumPy:** Data manipulation
- **PM4Py:** Event-log processing
- **SQL:** Business KPI analysis
- **Power BI:** Interactive data visualization

## Project Workflow

1. Initial data exploration and profiling
2. Data quality assessment and preparation
3. Procurement KPI development
4. Process and supplier analysis
5. SQL-based analysis
6. Power BI dashboard development
7. Findings, recommendations, and documentation

## Repository Structure

```text
procure-to-pay-analytics/
├── 01_data_exploration.ipynb
├── requirements.txt
└── README.md
```

The repository structure will expand as the analysis, SQL scripts, and dashboard are developed.

## Current Progress

- Loaded the event log into a Pandas DataFrame.
- Inspected dataset dimensions, columns, and data types.
- Checked missing values.
- Started profiling unique cases, documents, vendors, activities, and timestamps.

## Expected Outcome

A documented analytics project that connects procurement process data with business KPIs, evidence-based findings, and an interactive dashboard.

## Disclaimer

This is an analytical portfolio project. Any identified anomalies or potential inefficiencies will be treated as findings for investigation, not as proof of fraud or policy violations.
