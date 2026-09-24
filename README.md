# CRM & Call Center Analytics Dashboard – Power BI

## Project Overview

This project is an end-to-end CRM and Call Center Analytics solution developed using Microsoft Power BI.

The dashboard analyzes call activity, sales performance, agent performance, campaign performance, customer profiles, dispositions, and QA results.

The dataset used in this project is synthetic data generated using Python for portfolio and analytical practice. No real customer or organizational data is used.

The report contains five interactive analytical pages:

1. CRM Overview
2. Agent Performance
3. Campaign Analysis
4. Customer Insights
5. Call & Disposition Analysis

---

## Business Objective

The objective of this project is to provide a consolidated analytical view of CRM and call-center operations and help stakeholders monitor:

- Call volume and call outcomes
- Sales and conversion performance
- Agent and team performance
- Campaign performance
- Customer demographics and financial attributes
- Disposition trends
- QA pass/fail performance

---

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Python for synthetic data generation

---

## Dashboard Pages

### 1. CRM Overview

Provides a high-level view of CRM sales and call performance.

### 2. Agent Performance

Analyzes agent-level and team-level performance.

### 3. Campaign Analysis

Analyzes campaign performance, dialing modes, monthly sales, and geographic sales distribution.

### 4. Customer Insights

Provides customer-level demographic and financial analysis.

### 5. Call & Disposition Analysis

Analyzes call outcomes, disposition trends, call attempts, and QA performance.

---

## Key Metrics

- Total Calls
- Answered Calls
- Answer Rate %
- Total Sales
- Sales Conversion %
- Total Customers
- Total Campaigns
- Average Talk Time
- Average Wrap Time
- Average Sales per Campaign
- Average Customer Age
- Average Annual Income
- Average Credit Limit
- Average Outstanding Amount

---

## Power BI Features Implemented

- Data Modeling and Relationships
- DAX Measures
- Power Query Transformations
- Synced Slicers
- Page Navigation
- Reset Filters using Bookmarks
- Drill-down
- Drill-through
- Report Page Tooltip
- Conditional Formatting
- Edit Interactions
- Visual-level Filters
- Page-level Filters
- Report-level Filters
- Top N Filtering
- Time Intelligence
- Geographic Analysis using Maps

---

## Data Logic

- Customers are identified using unique mobile numbers.
- The same customer can appear in multiple campaigns.
- Each callable record has a separate unique record identifier.
- Customer-level metrics use unique customer logic.
- Record-level analysis uses callable record identifiers.

---

## Data Privacy

This project uses synthetic data generated using Python specifically for analytical and portfolio purposes.

No real customer, employee, banking, or organizational information is used or published in this repository.

Raw record-level datasets are intentionally not included in the public repository.
