# Data Structure

This folder contains the datasets used to build the Net Zero Transition Plan.

The data is structured to reflect a real-world ESG workflow, separating raw inputs from processed analytical tables.

---

## Structure

### raw/
Contains source-style ESG data used for carbon accounting:

- emissions baseline data
- Scope 1, 2, and 3 activity data
- supplier data (Scope 3)
- energy consumption
- financial inputs

These datasets simulate how companies typically store ESG data: fragmented, inconsistent, and requiring cleaning.

---

### processed/
Contains SQL-transformed datasets optimized for analysis and dashboarding:

- KPI tables
- scenario comparison
- financial modeling outputs
- abatement measures analysis

These tables were generated using SQL queries to simplify Power BI dashboard development and improve performance.

---

## Data Workflow

This project follows a real-world data pipeline:

raw data → data cleaning & transformation → structured tables → dashboard & insights

---

## Notes

- Data is a simplified representation for demonstration purposes
- Structure is inspired by real ESG and carbon accounting projects
