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
- Power BI dashboard with dedicated pages for overview, Scope 3 analysis, scenario modeling, financial impact, implementation roadmap, and abatement measures
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
- Executive-style dashboard pages for communicating insights to decision-makers

---

## Database Design

The project uses a SQLite database with **20 tables** covering emissions data, emission factors, carbon pricing, abatement measures, ROI calculations, payback timeline, and dashboard-ready KPI outputs.

Main database file:

```text
database/net_zero_2030_dashboard.db
```

The database follows a consulting-style ESG workflow:

1. Collect activity data
2. Apply emission factors
3. Calculate baseline emissions
4. Break down emissions by scope and category
5. Model decarbonization scenarios
6. Estimate abatement potential
7. Evaluate ROI and payback
8. Prepare dashboard-ready KPI tables

---

## Main Database Tables

### Emissions & Activity Data

- `activity_data`
- `baseline_emissions`
- `emission_factors`
- `scenario_emissions`

### Dimensions

- `dim_scope`
- `dim_year`

### Carbon Pricing & Financial Analysis

- `carbon_price`
- `measure_roi`
- `measure_benefits`
- `payback_timeline`

### Decarbonization & Abatement

- `abatement_measures`
- `abatement_potential`

### Dashboard Outputs

- `final_dashboard`
- `final_dashboard_kpi`
- `dashboard_scope_2023`
- `scope_breakdown_2023`
- `scope_3_breakdown`

### Company Context

- `company_profile`

---

## Dashboard Preview

The Power BI dashboard translates ESG and emissions data into executive-level insights for Net Zero planning, Scope 3 analysis, scenario modeling, implementation tracking, and financial decision-making.

### Overview

![Overview](dashboard/screenshots/overview.jpg)

### Scope 3 Analysis

![Scope 3 Analysis](dashboard/screenshots/scope-3-analysis.jpg)

### Scenario Analysis

![Scenario Analysis](dashboard/screenshots/scenario-analysis.jpg)

### Implementation Roadmap

![Implementation Roadmap](dashboard/screenshots/implementation-roadmap.jpg)

### Financial Impact

![Financial Impact](dashboard/screenshots/financial-impact.jpg)

### Abatement Measures

![Abatement Measures](dashboard/screenshots/abatement-measures.jpg)

---

## Key Insights

The analysis showed that:

- Scope 3 represented the largest share of total emissions
- Supplier engagement was the most important decarbonization lever
- Carbon pricing created a relevant long-term financial risk
- Some abatement measures had strong ROI and short payback periods
- Financial analysis helped prioritize which climate actions to implement first
- Dashboard-ready KPIs made the Net Zero strategy easier to communicate to decision-makers

---

## Tools Used

- **Power BI** – dashboard design and data visualization
- **SQLite** – relational database structure
- **SQL** – emissions analysis and KPI preparation
- **Excel** – input data structuring and analysis support
- **GHG Protocol** – Scope 1, 2, and 3 emissions logic
- **ESG reporting frameworks** – reporting-oriented structure and communication

---

## Skills Demonstrated

This project demonstrates skills relevant to ESG, sustainability, and carbon data roles:

- Carbon accounting
- GHG inventory design
- Scope 1, 2, and 3 emissions analysis
- ESG data modeling
- SQL database structuring
- Power BI dashboarding
- Climate strategy analysis
- Carbon pricing analysis
- Decarbonization planning
- ROI and payback analysis
- ESG reporting communication
- Executive-level sustainability insights

---

## Repository Structure

```text
net-zero-dashboard/
│
├── README.md
├── data/
│   ├── raw/
│   └── processed/
├── database/
│   ├── README.md
│   └── net_zero_2030_dashboard.db
├── dashboard/
│   └── screenshots/
│       ├── overview.jpg
│       ├── scope-3-analysis.jpg
│       ├── scenario-analysis.jpg
│       ├── implementation-roadmap.jpg
│       ├── financial-impact.jpg
│       └── abatement-measures.jpg
├── reports/
│   └── README.md
└── docs/
    ├── methodology.md
    └── assumptions.md
```

---

## Methodology

The project follows the GHG Protocol structure.

### Scope 1

Direct emissions from company-owned or controlled sources.

### Scope 2

Indirect emissions from purchased electricity.

### Scope 3

Indirect value chain emissions, including supplier-related and other upstream/downstream categories.

The analysis connects activity data with emission factors to calculate emissions by year, scope, and category.

Decarbonization measures are evaluated based on:

- Emissions reduction potential
- Implementation cost
- Annual savings
- ROI
- Payback period
- Strategic feasibility
- Carbon pricing exposure

---

## Business Value

This project shows how ESG data can support better business decisions.

The dashboard and database help sustainability teams:

- Identify emissions hotspots
- Understand Scope 3 exposure
- Prioritize decarbonization measures
- Evaluate financial return from climate initiatives
- Communicate sustainability strategy to executives
- Track progress toward Net Zero targets
- Prepare structured ESG reporting outputs

---

## Use Case

This project is relevant for organizations that need to:

- Build a GHG inventory
- Analyze Scope 1, 2, and 3 emissions
- Develop a Net Zero transition plan
- Understand supplier-related emissions
- Evaluate decarbonization investments
- Create ESG dashboards for internal decision-making
- Translate sustainability data into financial and strategic insights

---

## About the Project

This is a simulated project created for portfolio purposes.

The data is sample/synthetic and is used to demonstrate ESG analytics, carbon accounting, SQL data modeling, and dashboard reporting skills.

---

## Author

**Christian Seymand**  
ESG & Carbon Data Analyst

I help ESG teams build carbon inventories, dashboards, and reporting workflows.

Portfolio: [christianseymand.crd.co](https://christianseymand.crd.co/)  
LinkedIn: [linkedin.com/in/christian-seymand-934244137](https://linkedin.com/in/christian-seymand-934244137/)
