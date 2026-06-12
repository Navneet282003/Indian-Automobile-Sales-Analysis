# 🚗 Indian Automobile Sales Analysis

## Project Overview
This project presents an end-to-end data analysis of the Indian 
automobile market, tracking sales performance of 94 car models 
across 14 major companies over a 6-month period 
(November 2025 – April 2026).

The analysis was built on a MySQL relational database and 
visualized through an interactive Power BI dashboard, uncovering 
market trends, seasonal patterns, and brand-level insights.

## Problem Statement
The Indian automobile market is highly dynamic with dozens of 
brands competing across multiple vehicle segments. Understanding 
which models are gaining momentum, which segments dominate, and 
how sales fluctuate month-over-month is critical for business 
decision-making in areas like inventory planning, marketing 
strategy, and product launches.

## Objectives
- Analyse 6-month sales trends across India's top automobile brands
- Identify best-selling models and dominant vehicle segments
- Compute Month-on-Month (MoM%) changes to detect seasonal patterns
- Compare performance across SUV, Sedan, Hatchback, EV, MPV segments
- Build an interactive Power BI dashboard for data-driven insights

## Dataset
- **product_details** — 94 models with company name, base price, 
  top price and vehicle type
- **sales_final** — Monthly sales figures for each model across 
  6 months (Nov 2025 – Apr 2026)
- Tables connected via Model_Name as the primary join key

## Tools & Technologies
| Tool | Purpose |
|---|---|
| MySQL | Database design, storage, querying |
| Power BI | Dashboard, visualizations |
| DAX | Custom measures, KPI calculations |
| Power Query | Data transformation, unpivoting |

## Key Findings
- 🏆 **Maruti Suzuki** leads with 40.3% market share and 7 of 
  the Top 10 bestselling models
- 🚙 **SUVs dominate** at 56.9% of total sales — reflecting 
  India's shift toward utility vehicles
- 📊 **Tata Nexon** is the #1 model overall with 1.22 lakh 
  units in 6 months
- 📉 **February 2026** saw the sharpest market dip (-5.52% MoM) 
  — a recurring seasonal pattern post-budget
- 📈 **April 2026** recorded the strongest recovery (+2.55% MoM) 
  driven by new model launches
- 🔋 **EVs remain at 1.1%** of total sales despite 10+ models 
  — price and infrastructure barriers persist
- 💰 **Budget segment** (under ₹10L) dominates volume while 
  premium SUVs show high price but low sales

## Dashboard Features
- KPI Cards — Total Sales, Best Model, SUV Sales, Top Segment
- Sales by Company Treemap with drill-down to model level
- Top 10 Models ranked bar chart
- MoM% Heatmap Matrix with Red/Green conditional formatting
- Vehicle Segment breakdown with average price comparison
- Month slicer for dynamic filtering across all visuals
