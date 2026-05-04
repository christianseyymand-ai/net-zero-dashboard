# Methodology

This document explains the methodology used in the Net Zero 2030 – Carbon Strategy Dashboard project.

## 1. Project Objective

The objective of this project is to simulate how a company can structure, analyze, and visualize ESG and carbon data to support a Net Zero transition strategy.

The project combines:

- Carbon accounting
- Scope 1, 2, and 3 emissions analysis
- SQL-based data modeling
- Power BI dashboarding
- Carbon pricing analysis
- Decarbonization planning
- ROI and payback analysis

---

## 2. Carbon Accounting Framework

The emissions structure follows the GHG Protocol approach.

### Scope 1

Scope 1 includes direct emissions from sources owned or controlled by the company.

Examples:

- Fuel combustion
- Company vehicles
- On-site energy use

### Scope 2

Scope 2 includes indirect emissions from purchased electricity.

Examples:

- Electricity consumption
- Purchased energy used in operations

### Scope 3

Scope 3 includes indirect emissions across the company’s value chain.

Examples:

- Purchased goods and services
- Supplier-related emissions
- Logistics and transportation
- Business travel
- Waste
- Use of sold products

---

## 3. Data Structure

The project uses a SQLite database to organize ESG and emissions data.

The database includes:

- Activity data
- Emission factors
- Baseline emissions
- Scope-level emissions
- Scenario emissions
- Carbon pricing
- Abatement measures
- ROI and payback calculations
- Dashboard-ready KPI tables

This structure allows emissions data to be analyzed by:

- Year
- Scope
- Category
- Scenario
- Decarbonization measure

---

## 4. Emissions Calculation Logic

The general emissions calculation logic is:

Activity Data × Emission Factor = Emissions

Emissions are expressed in tCO₂e.

The project uses sample/synthetic data to demonstrate the workflow.

---

## 5. Baseline Year

The baseline year used in this project is 2023.

The baseline emissions inventory is used as the starting point for:

- Scope breakdown analysis
- Scenario modeling
- Net Zero roadmap
- Decarbonization strategy
- Carbon cost exposure analysis

---

## 6. Scenario Modeling

The project includes scenario-based emissions modeling to compare different pathways.

Scenarios may include:

- Business-as-usual emissions
- Partial decarbonization
- Net Zero 2030 pathway
- Long-term transition pathway

Scenario modeling helps evaluate whether the company can reduce emissions fast enough to meet its climate goals.

---

## 7. Abatement Measures

Abatement measures are used to estimate potential emissions reductions.

Each measure can be evaluated based on:

- Scope
- Category
- Start year
- Reduction potential
- Implementation cost
- Annual financial benefit
- Strategic relevance

---

## 8. Financial Analysis

The project connects decarbonization measures with financial indicators.

Key financial metrics include:

- CAPEX
- Annual benefit
- ROI
- Payback period
- Carbon pricing exposure
- Cost avoidance

This helps prioritize climate actions based on both environmental and financial impact.

---

## 9. Dashboard Preparation

Final tables are prepared for Power BI visualization.

The dashboard is designed to help users understand:

- Total emissions
- Scope 1, 2, and 3 breakdown
- Scope 3 hotspots
- Emissions scenarios
- Carbon pricing impact
- ROI of decarbonization measures
- Net Zero progress

---

## 10. Limitations

This project is a simulated portfolio project.

The data is sample/synthetic and should not be interpreted as real company data.

The purpose of the project is to demonstrate ESG analytics, carbon accounting, data modeling, and dashboard reporting skills.
