# NovaTech Revenue Intelligence Dashboard

## Project Overview

The **NovaTech Revenue Intelligence Dashboard** is a business intelligence project developed for the Udacity AI Business Professional Nanodegree final project.

The project brings together NovaTech's **CRM deals, marketing campaigns, and customer support data** into a unified analysis environment using **Amazon Quick**. The dashboard provides cross-functional visibility into revenue performance, marketing activity, sales performance, and customer health.

The project also uses **Quick Chat and a configured Topic** to enable natural-language business analysis across the unified dataset.

---

## Business Context

NovaTech Solutions is a mid-size B2B SaaS company whose business data is distributed across multiple systems:

- CRM and sales data
- Marketing campaign data
- Customer support data

The objective of this project is to create a unified revenue intelligence solution that helps business stakeholders analyze these areas together and explore the data using natural-language questions.

---

## Project Objectives

The project focuses on:

- Combining CRM, marketing, and support data using a shared `account_id`
- Preparing and validating the source datasets
- Creating a unified dataset for cross-functional analysis
- Building an interactive three-view dashboard
- Creating calculated business metrics
- Enabling natural-language analysis through Quick Chat
- Validating AI-generated answers against dashboard results
- Communicating key findings and recommended business actions

---

## Data Sources

The project uses three primary datasets:

| Dataset | Records | Columns |
|---|---:|---:|
| CRM Deals | 499 | 20 |
| Marketing Campaigns | 2,240 | 20 |
| Support Tickets | 3,000 | 20 |

A unified dataset was also created by joining the three source datasets using the shared account identifier.

### Unified Dataset

- **Rows:** 63,420
- **Columns:** 62
- **Storage:** SPICE

All three source datasets and the unified dataset were imported into SPICE.

---

## Data Preparation

The data preparation process included:

- Reviewing dataset structure and data quality
- Correcting data types
- Validating row and column counts
- Checking important categorical and numerical fields
- Creating calculated fields
- Joining CRM, marketing, and support datasets
- Importing the resulting datasets into SPICE
- Performing independent verification checks

### Calculated Fields

Two important calculated fields were created:

**Days to Close**

Measures the number of days between deal creation and deal closure.

**Campaign ROI**

Measures campaign return relative to campaign spend.

---

## Dashboard

The final dashboard contains three analytical views.

### 1. Marketing Funnel

Focuses on marketing campaign performance and conversion activity.

Key analysis includes:

- Total attributed revenue
- Revenue by marketing channel
- Campaign ROI
- Campaign response rate
- Marketing funnel stages
- Campaign and customer-segment filtering

### 2. Sales Pipeline

Focuses on sales performance and deal outcomes.

Key analysis includes:

- Deal outcomes
- Win rate by sales region
- Revenue by product
- Average days to close
- Average deal value
- Deals lost by reason
- Average deal size by company size

### 3. Customer Health

Focuses on customer support activity and customer health indicators.

Key analysis includes:

- Total support tickets
- Ticket volume by account
- Average resolution time
- Support tickets by product area
- Customer sentiment distribution
- Customer risk indicators

The dashboard also includes interactive filters, visual interactions, and cross-sheet navigation.

---

## AI-Powered Analysis

A Quick Chat Topic named:

**NovaTech Revenue Intelligence**

was configured using the unified NovaTech dataset.

The Topic provides business context for:

- Revenue analysis
- Sales analysis
- Marketing analysis
- Customer support analysis
- Account-level analysis

The configuration emphasizes distinct identifiers such as:

- `opportunity_id` for CRM deals
- `lead_id` for marketing leads
- `ticket_id` for support tickets
- `account_id` as the common account identifier

The project includes baseline and post-Topic Quick Chat questions to examine how the configured Topic affects natural-language analysis.

---

## AI Validation

The project includes an **AI Q Exploration Log** containing five business questions spanning:

- Marketing
- Sales
- Customer support
- Cross-functional analysis

The Quick Chat responses were compared with dashboard results and documented as:

- Match
- Partial Match
- No Match

This validation highlights both areas of agreement and differences between natural-language analysis and dashboard calculations.

---

## Data Quality & Verification

A verification log containing six validation questions was created across the three source datasets.

The verification covered:

- CRM
- Marketing
- Customer Support

The checks included categorical distributions, missing values, and business-related data characteristics.

Additional evidence is included for:

- Data type corrections
- Calculated fields
- Dataset joins
- SPICE ingestion
- Unified dataset creation

---

## Key Project Deliverables

The submission folder contains supporting evidence and documentation, including:

- Dashboard screenshots
- SPICE dataset evidence
- Data preparation evidence
- Join configuration evidence
- Calculated-field evidence
- Verification Log
- Q Exploration Log
- Quick Chat / Topic evidence
- Dashboard PDF
- Executive Report

---

## Tools & Technologies

- **Amazon Quick / QuickSight**
- **SPICE**
- **Quick Chat**
- **QuickSight Topics**
- CSV datasets
- Data visualization
- Business intelligence analysis

---

## Project Outcome

The completed solution provides a unified analytical view of NovaTech's marketing, sales, revenue, and customer support information.

The project demonstrates the use of business intelligence dashboards together with natural-language AI analysis to support cross-functional revenue analysis and business decision-making.

---

## Author

**Sourish Dikkala**

B.Tech — Computer Science & Engineering (AI & ML)

**Udacity AI Business Professional Nanodegree**
