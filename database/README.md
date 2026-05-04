# Database Documentation

This folder contains the SQLite database used for the Net Zero 2030 – Carbon Strategy Dashboard project.

## Main Database

`net_zero_2030_dashboard.db`

## Purpose

The database structures emissions, activity data, emission factors, carbon pricing, abatement measures, ROI calculations, payback timeline, and dashboard-ready outputs.

## Main Tables

### Emissions & Activity Data

- `activity_data`
- `baseline_emissions`
- `emission_factors`
- `scenario_emissions`

### Dimensions

- `dim_scope`
- `dim_year`

### Decarbonization & Abatement

- `abatement_measures`
- `abatement_potential`
- `measure_benefits`
- `measure_roi`
- `payback_timeline`

### Dashboard Outputs

- `final_dashboard`
- `final_dashboard_kpi`
- `dashboard_scope_2023`
- `scope_breakdown_2023`
- `scope_3_breakdown`

### Company Context & Financial Inputs

- `company_profile`
- `carbon_price`

## Workflow

1. Activity data is organized by year, scope, and category.
2. Emission factors are applied to estimate emissions.
3. Baseline emissions are calculated for the reference year.
4. Decarbonization scenarios are modeled.
5. ROI and payback are calculated.
6. Final KPI tables are prepared for Power BI.
