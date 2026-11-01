# Retirement Plan Performance & Cost Monitor
## Analytical Methodology & Project Documentation

### 1. Business Objective
To design an institutional retirement plan review model supporting data integration, participant monitoring, investment performance tracking, and cost efficiency analysis for corporate plan sponsors (simulating operational standards for Shuster Advisory Group).

### 2. Data Engineering & Synthetic Generation Strategy
* **Participant Census (`Participant_Census.xlsx`):** Simulates 350 active employee records across four distinct retirement plan structures: **401(k), 403(b), 457(b), and Defined Benefit (DB) plans**. Attributes include employee identifiers, division mapping, age distribution, annual salaries, deferral percentages, and computed annual contributions.
* **Fund Performance & Costs (`Fund_Performance_Costs.xlsx`):** Simulates a 9-fund institutional lineup spanning large-cap equity, fixed income, target-date retirement funds, and stable value options. Tracks beginning assets under management (AUM), net cash flows, year-to-date returns, ending AUM, and explicit **fund expense ratios** to evaluate plan cost efficiency.

### 3. Analytical Framework & KPI Tracking (`Shuster_Advisory_Group_Retirement_Analytics_Model.xlsx`)
* **Participation Monitoring:** Calculates active participation rates by segmenting contributors from non-contributing participants across plan types using dynamic Excel formulas (`COUNTIF`, `AVERAGEIF`, `SUMIF`).
* **Cost Efficiency Analysis:** Evaluates weighted average expense ratios against institutional benchmark targets to ensure fiduciary compliance and fee transparency.
* **Reporting Architecture:** Multi-tab executive dashboard structured for presentation-ready client reviews and professional portfolio display.
