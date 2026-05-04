# Net Zero 2030 – Carbon Strategy Dashboard

ESG analytics project combining carbon accounting, SQL data modeling, Power BI dashboarding, and financial analysis to evaluate a Net Zero transition strategy.

This project simulates a full ESG consulting engagement where a company needs to understand its Scope 1, 2, and 3 emissions, identify carbon hotspots, evaluate decarbonization measures, and translate sustainability data into business and financial decisions.

---

## Project Summary

The goal of this project is to show how ESG and emissions data can be structured, analyzed, and visualized to support a Net Zero strategy.

The solution includes:

- A Scope 1, 2, and 3 GHG emissions inventory
- A SQLite database with structured ESG and carbon data
- SQL-based emissions analysis
- Power BI dashboard outputs
- Carbon pricing analysis
- Abatement measures and reduction potential
- ROI and payback analysis
- Dashboard-ready KPI tables
- A Net Zero transition roadmap

---

## Business Challenge

A company with **45,805 tCO₂e annual emissions in the 2023 baseline year** needed to evaluate how to move toward Net Zero by 2030.

Key challenges:

- Most emissions came from Scope 3 value chain activities
- Supplier-related emissions were difficult to manage
- ESG data was fragmented across different categories
- The company needed to prioritize decarbonization measures
- Management needed a clear view of climate impact, cost, ROI, and payback
- The company needed dashboard-ready outputs for decision-making

---

## Solution Built

I developed an end-to-end ESG analytics solution that connects carbon accounting, data modeling, financial analysis, and dashboard reporting.

The project includes:

- Emissions activity data organized by year, scope, and category
- Emission factors used to estimate carbon emissions
- Baseline emissions by Scope 1, Scope 2, and Scope 3
- Scenario-based emissions modeling
- Carbon pricing exposure analysis
- Abatement measures by scope and category
- Reduction potential by year
- ROI and payback analysis for decarbonization initiatives
- Final dashboard tables prepared for Power BI

---

## Database Design

The project uses a SQLite database with **20 tables** covering emissions data, emission factors, carbon pricing, abatement measures, ROI calculations, payback timeline, and dashboard-ready KPI outputs.

Main database file:

```text
database/net_zero_2030_dashboard.db
