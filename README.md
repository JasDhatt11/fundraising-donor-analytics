# Fundraising & Donor Analytics

**SQL | Power BI | DAX | Data Modeling | Excel | Simulated Data**

## Overview

This project analyzes a simulated nonprofit fundraising dataset to understand donation revenue, donor behaviour, and campaign performance.

The analysis was built around a practical question: **Where is fundraising revenue coming from, which campaigns are performing well, and what patterns in donor activity are worth paying attention to?**

I designed the underlying donor, campaign, and donation structure, analyzed the data using SQL, and built a Power BI dashboard to turn the results into usable performance measures.

## Business Questions

The analysis focuses on:

* How much total donation revenue was generated?
* Which campaigns generated the most revenue?
* How does revenue vary by province?
* What contribution comes from different donor types?
* Which donation types generate the most revenue?
* How are campaigns performing against their targets?
* How many donors are repeat donors?
* What patterns can be identified in donor activity?

## Data & Model

The project uses three core entities:

* **Donors** — donor information and donor classification
* **Campaigns** — campaign information and fundraising targets
* **Donations** — individual donation transactions linking donors and campaigns

The relational structure allows donation activity to be analyzed across donor and campaign dimensions rather than treating the fundraising data as a single flat table.

## SQL Analysis

SQL was used to calculate and validate the core fundraising measures.

Examples include:

* Total donation revenue
* Donation transaction counts
* Campaign-level revenue
* Revenue by province
* Revenue by donor type
* Revenue by donation type
* Repeat donor activity
* Campaign target versus actual performance

Aggregation, joins, grouping, filtering, and ordering were used to move from individual transactions to management-level performance measures.

## Power BI Analysis

The Power BI model connects the donor, campaign, and donation data to provide interactive reporting.
<img width="1798" height="990" alt="image" src="https://github.com/user-attachments/assets/fb879b41-125f-4553-91fc-74ddbb61549a" />


### Key KPIs

* **Total Donation Revenue:** $9,600
* **Donation Transactions:** 30

Additional measures were created to examine donor and campaign performance from different perspectives.

## Key Analysis Areas

### Campaign Performance

Campaign revenue was compared with fundraising targets to identify stronger and weaker campaign performance.

This provides a more useful view than looking only at total revenue because it considers performance relative to the intended fundraising goal.

### Donor Analysis

Donors were segmented by characteristics such as donor type and province to understand where fundraising activity is concentrated.

Repeat donor analysis was also used to distinguish one-time contribution activity from ongoing donor engagement.

### Donation Analysis

Revenue was examined by donation type to understand how different contribution methods contribute to overall fundraising revenue.

## Business Value

The dashboard provides a simple way for a fundraising team to move from transaction-level data to performance-level analysis.

The analysis can help support questions such as:

* Where should fundraising attention be concentrated?
* Which campaigns require additional support?
* Which donor groups contribute the most revenue?
* Where is repeat donor activity strongest?
* Are campaigns meeting their intended fundraising targets?

## Tools Used

* **SQL** — querying, aggregation, joins and validation
* **Power BI** — dashboard development and reporting
* **DAX** — analytical measures and KPIs
* **Excel** — data preparation and review
* **Data Modeling** — relational donor, campaign and donation structure

## Project Outcome

The final result is an end-to-end fundraising analytics workflow that moves from structured data and SQL analysis to an interactive Power BI dashboard.

The project demonstrates the ability to take a business question, structure the underlying data, develop measurable KPIs, investigate performance patterns, and present the findings in a form that can support decision-making.
