# Electric Vehicle Market & Adoption Analytics Dashboard

An interactive Business Intelligence dashboard built in Tableau to analyze electric vehicle (EV) registration trends, battery tech adoption, and manufacturer market share across key geographic regions.

**[View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/thao.lu6343/viz/Electric_Vehicle_Dashboard_17324843935220/Dashboard1)**

---

## Strategic Questions This Dashboard Answers

This tool transforms complex vehicle registration data into visual insights to help urban planners, energy providers, and industry analysts answer critical strategic questions:

* **Infrastructure & Site Selection:** *Where should energy companies and cities prioritize building new charging stations?*  
  Maps high-density EV regions and identifies areas with shorter average battery ranges that urgently require fast-charging infrastructure.
* **Grid Planning & Power Demand:** *How much energy demand will new EV registrations place on local utility grids?*  
  Tracks the growth ratio of fully electric vehicles (BEVs) versus plug-in hybrids (PHEVs) to help utility providers forecast regional power spikes.
* **Competitive Intelligence:** *Which automakers are dominating the market, and how are legacy brands catching up?*  
  Ranks top manufacturers by registration volume and tracks brand market share changes over model years.
* **Policy & Incentive Impact:** *Are clean energy incentives successfully driving adoption in target communities?*  
  Evaluates Clean Alternative Fuel Vehicle (CAFV) eligibility rates to measure the reach of state and federal EV tax incentives.

---

## Core Dashboard Features

* **Executive KPI Cards:** Real-time summary of total EV volume, average electric range, and BEV vs. PHEV market distribution.
* **Geographic Mapping:** Visual density analysis by state and county to spot high-growth regions.
* **Historical Trend Analysis:** Registration trajectory charted across model years to measure adoption momentum.
* **Dynamic Slicing & Filtering:** Interactive controls for **Model Year**, **Vehicle Type**, and **Make/Model** for deep-dive exploratory analysis.

---

## Technical Execution

* **Calculated Fields & Expressions:** Built custom ratios, dynamic averages, and aggregations for key fleet metrics.
* **Interactive Dashboard Architecture:** Configured global action filters, dynamic tooltips, and cross-filtering across views for seamless navigation.
* **Visual Data Storytelling:** Designed a structured layout hierarchy and intuitive color scheme to communicate insights clearly to stakeholders.

---

## 📂 Repository Contents

* `Electric_Vehicle.twbx` — Downloadable Tableau Packaged Workbook containing the dashboard model and calculated fields.
* `data/` — Raw EV registration dataset.
