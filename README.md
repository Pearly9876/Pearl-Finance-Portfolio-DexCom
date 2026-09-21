# 📊 DexCom Finance Analyst Project

## Objective

The objective of this project is to analyse DexCom's historical financial performance, identify the key business drivers, and build a forward-looking financial forecast with scenario analysis.

---

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Why Dexcom](#why-dexcom)
- [Historical Analysis](#historical-analysis)
- [Driver Analysis](#driver-analysis)
- [Forecasting](#forecasting)
- [Scenario Analysis](#scenario-analysis)
- [Key Insights](#key-insights)
- [Dashboard](#dashboard)
- [Project files](#project-files)

---

## Project Overview

This project analyses DexCom's historical financial performance and develops a forward-looking FP&A model.


| Area | Details |
|---|---|
| Company | DexCom |
| Project Type | FP&A / Financial Analysis |
| Historical Period | 2017–2025 |
| Forecast Period | 2026–2030 |
| Key Analysis | Revenue growth, margins, cash flow, CapEx, working capital |
| Forecasting | Driver-based financial forecast |
| Scenario Planning | Base Case, Upside Case, Downside Case |
| Tools | Excel |
| Data Source | SEC filings, DexCom Annual Reports, Investor Relations |
| Final Output | Financial model, scenario analysis and business insights |

---

## Data Source

The analysis is based on DexCom's publicly available financial information, including:

- Annual Reports / Form 10-K filings (https://investors.dexcom.com/financials/annual-reports/default.aspx)
- SEC filings (https://www.sec.gov/edgar/browse/?CIK=1093557&owner=exclude)
- Investor realtions (https://investors.dexcom.com/overview/)

---

## Why Dexcom

I chose DexCom after researching the long-term growth of diabetes and the increasing use of technology in healthcare.

Diabetes is expected to remain a major global health issue over the coming decades. Its prevalence is influenced by factors including ageing, lifestyle and genetics, creating an ongoing need for better glucose monitoring solutions.

DexCom focuses on continuous glucose monitoring (CGM), which allows users to track glucose levels in real time.

This made DexCom an interesting company for my FP&A project because its growth is connected to three key areas:

**Growing diabetes population → Increasing adoption of CGM technology → Potential expansion of DexCom's addressable market**

Rather than analysing the company only from its historical financial performance, I wanted to understand whether these underlying business drivers could support future revenue growth, margins and cash flow.

---

## Historical Analysis

I used AI-assisted data extraction to collect historical financial data, then independently reviewed, recalculated and reconciled the financial statements before using the data for analysis.

### Process

1. Collected historical financial data from 2018–2025.
2. Standardised the Profit & Loss, Balance Sheet and Cash Flow statements.
3. Recalculated key totals and reconciled differences to check data accuracy.
4. Used the verified historical data to calculate growth, margins, cash flow and working capital metrics.

### Analysis Framework

| Step | Area | What I Analysed | Output |
|---|---|---|---|
| 1 | Growth & Profitability | Revenue, gross margin, operating margin, R&D and SG&A | Growth and margin trend |
| 2 | Cash Flow & Reinvestment | Operating cash flow, CapEx, free cash flow, cash conversion | Cash generation and reinvestment trend |
| 3 | Working Capital | Accounts receivable, inventory, accounts payable, AR days and inventory days | Working capital efficiency trend |

### Key Question

> Has DexCom's revenue growth translated into stronger profitability and sustainable cash flow?

### Step 1 — Growth & Profitability

**Business question:** How has Dexcom's cost structure evolved as revenue growth moderated?

***[ Chart 1A — Revenue Growth vs Cost Structure ]***
Historical performance | 2018–2025

<img width="897" height="497" alt="image" src="https://github.com/user-attachments/assets/9a825287-8ad2-4601-9a46-e339fbf98205" />


**Key insights**
- Revenue growth moderated as the business scaled, declining from above 40% in 2018–2019 to 16% in 2025.
- SG&A declined from 42% to 28% of revenue, while R&D decreased from 19% to 13%, indicating improving operating leverage as revenue scaled.
- In contrast, COGS increased to 40% of revenue by 2025, suggesting that gross-margin pressure remained despite improved operating expense efficiency.

**Metrics:** Revenue growth · COGS / Revenue · R&D / Revenue · SG&A / Revenue

***[ Chart 1B — Profitability Trend ]***
Historical performance | 2018–2025

<img width="721" height="436" alt="image" src="https://github.com/user-attachments/assets/14480a34-c55c-4805-a7f4-ad9667f63d32" />

**Key insights**
- Gross margin remained relatively stable, although it softened from its peak in 2020–2021.
- Operating leverage improved as SG&A and R&D declined as a percentage of revenue, helping operating margin expand significantly over time.
- Net margin also strengthened and moved closer to operating margin by 2025, suggesting that revenue growth was translating into stronger overall profitability.


### Step 2 — Cash Flow & Reinvestment

**Business question:** Is profit translating into sustainable cash generation?

![Cash Flow Trend](images/cash-flow-trend.png)

**Key insights**
- CFO margin improved over time, showing stronger cash conversion as the business scaled.
- CapEx remained elevated as Dexcom continued investing in manufacturing capacity and operational expansion.
- Despite continued reinvestment, free cash flow expanded, indicating improving cash efficiency.

**Metrics:** Operating cash flow · CapEx · Free cash flow · Cash conversion

### Step 3 — Working Capital

**Business question:** How is business growth affecting working capital requirements?

![Working Capital Trend](images/working-capital-trend.png)

**Key insights**
- Receivables and inventory moved materially as the business expanded.
- AR days and inventory days were not stable across the historical period.
- These movements were reviewed as potential assumptions for the forecast.

**Metrics:** Accounts receivable · Inventory · Accounts payable · AR days · Inventory days
 
---

## Driver Analysis

In this step, I reviewed DexCom's management discussion and annual reports to identify the key drivers behind revenue, gross margin and operating expenses.

I focused on understanding which drivers were recurring and structural, and which were temporary or one-off items. This included revenue growth, product and channel mix, manufacturing costs, R&D, SG&A and other operating expenses.

### Key Driver Findings

| Area | Key Drivers Identified |
|---|---|
| Revenue | Customer growth, higher sensor volumes and market expansion |
| Gross Margin | Product mix, channel mix, manufacturing efficiency and temporary charges |
| R&D | Product development and technology investment |
| SG&A | Commercial expansion, higher headcount and international growth |

### Structural vs One-off Drivers

| Structure& Recurring | Temporary & One - off |
|---|---|
| Customer and sensor volume growth | Inventory-related charges
| R&D investment | Freight pressures
|Sales and marketing spending |  Inventory damaged in transit
|International expansion | Production yield issues

### Key Insight

Revenue growth appears to be mainly supported by expanding customer adoption and sensor volumes, while DexCom continues to invest heavily in R&D and commercial expansion.

Some gross margin pressure was driven by temporary operational factors, while other costs reflect longer-term investment required to support growth.

---

## Forecasting

In this stage, I developed a financial forecast for 2026–2030 based on DexCom's historical performance and the key business drivers identified in the previous analysis.

I used CFI's three-statement modelling tutorial as a learning reference to understand the forecasting structure and logic. I then adapted the framework to DexCom and built the forecast assumptions step by step in Excel.

[Financial Modeling Tutorial | Build a Three-Statement Model in 30 Minutes with CFI CEO Tim Vipond](https://www.youtube.com/watch?v=UMYDxmiVin4&t=1247s)

### Forecasting Process

1. Reviewed historical financial trends and key business drivers.
2. Identified the assumptions required for each financial statement.
3. Built forecast assumptions for revenue, margins, operating expenses, working capital and CapEx.
4. Linked the assumptions into the P&L, Balance Sheet and Cash Flow Statement.
5. Checked that the three financial statements remained internally consistent.
6. Used the completed model as the base for scenario analysis.

### Key Forecast Assumptions

| Area | Forecast Driver |
|---|---|
| Revenue | Historical growth + business outlook |
| Gross Margin | Historical margin trend + operational drivers |
| R&D | % of revenue |
| SG&A | % of revenue |
| Working Capital | AR, inventory and payable assumptions |
| CapEx | % of revenue |
| D&A | Linked to PPE / historical trend |
| Tax | Effective tax rate |

### Forecast Assumption Model

![Forecast Assumptions](images/forecast-assumptions.png)

The assumption sheet acts as the control centre of the model, allowing key drivers to flow through the three financial statements.


---

## Scenario Analysis

I developed three scenarios — Base, Upside and Downside — using a single scenario selector linked to the forecast assumptions.

By changing one input, the model updates the key assumptions and flows through the P&L, Balance Sheet and Cash Flow Statement automatically.

The scenario analysis focuses on the assumptions that have the greatest impact on financial performance, including revenue growth, margins, operating expenses, working capital and CapEx.

*****

---

## Key Insights

The final stage converts financial analysis into business insights.

The objective is not only to calculate numbers, but also to understand:

> What is driving the result?

> What could change the forecast?

> What should management monitor?


---

## Dashboard

---


## Project files

---
