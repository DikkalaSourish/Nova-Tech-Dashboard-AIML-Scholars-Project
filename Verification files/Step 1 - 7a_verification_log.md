# NovaTech Data Verification Log

**Student Name:** Sourish Dikkala

**Date:** 11-09-2026

## Instructions

Query each pre-indexed knowledge base using Quick Chat. For each question, record the expected answer (from the data dictionary), Q's actual response, and whether they match. Minimum 6 entries (2 per data knowledge base).

## Verification Log

| # | Knowledge Base | Question Asked | Expected Answer | Q's Actual Answer | Match? | Notes |
|---|----------------|---------------|-----------------|-------------------|--------|-------|
| 1 | NovaTech CRM Deals | Which sales regions are represented in the CRM deals? | Central, East, and West — 3 regions. | Q identified Central, East, and West as the sales regions. | Yes | The Q response matched the expected regions in the CRM data. |
| 2 | NovaTech CRM Deals | How many CRM deals have no revenue and why is the revenue zero? | 184 deals have zero deal value, corresponding to Lost deals. | Q reported 184 deals with zero revenue and explained that they were Lost deals. | Yes | The result matched the CRM data definition that Lost deals have a deal value of zero. |
| 3 | NovaTech Marketing Campaigns | Which countries are represented by the market source codes? | AU, CA, DE, ES, IN, MX, SA, and US. | Q identified Australia, Canada, Germany, Spain, India, Mexico, Saudi Arabia, and the United States. | Yes | The country names matched the market source codes in the data. |
| 4 | NovaTech Marketing Campaigns | How many marketing records have a missing annual income value? | 24 records, approximately 1.1% of marketing records. | Q reported 24 missing annual income values, approximately 1.1%. | Yes | The Q response matched the expected missing-value count and percentage. |
| 5 | NovaTech Support Tickets | What is the priority distribution of support tickets? | Low: 1,500; Medium: 1,050; High: 400; Critical: 50. | Q reported Low 1,500, Medium 1,050, High 400, and Critical 50 tickets. | Yes | The priority counts matched the expected distribution. |
| 6 | NovaTech Support Tickets | What sentiment categories are present, and are there any missing sentiment values? | Negative, Neutral, and Positive; no missing sentiment values. | Q identified Negative, Neutral, and Positive sentiment categories and no missing values. | Yes | The Q response matched the expected sentiment categories and completeness. |
| 7 | NovaTech Reference Documents | | | | | |

## Cross-Check

Pick one fact from above and confirm it independently in the QuickSight dataset preview.

- **Fact verified:** Low-priority tickets are present in the Support Tickets dataset.
- **Chat said:** Q identified Low as one of the support ticket priority categories, with 1,500 tickets.
- **QuickSight shows:** The dataset preview contains multiple support ticket records where the priority field is set to "low".
- **Consistent?:** Yes
