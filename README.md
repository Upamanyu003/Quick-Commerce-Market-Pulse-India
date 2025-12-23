# Quick Commerce Market Pulse — India

An end-to-end Power BI analysis of India's quick commerce ecosystem, focusing on **market structure, operational performance, and demand quality**.
The project goes beyond surface-level growth metrics to diagnose **SLA stress, peak-hour bottlenecks, and discount-driven demand patterns**.
---

## Project Objective 

To assess if rapid growth in quick commerce is:
- operationally sustainable
- Backed by reliable delivery performance
- Driven by healthy, high-quality demand - and not promotions alone
---

## 📊Dashboard Structure

### Page 1 — Market Overview
- Competitive Landscape of Major Platforms
- Market share, order volume, revenue, and AOV comparison
- Metro vs. non-metro demand concentration

**Key takeaway:**
Quick commerce is a large, concentrated, and execution-driven market.

---

### Page 2 — Operational Performance & SLA Stress
- Average delivery time versus 15-minute SLA benchmark
- City-level and platform-level SLA breach analysis
- Peak-hour demand versus delivery performance

**Key takeaway:** 
More than 65% of the orders breach the SLA; failures spike during evening peak hours, indicating systemic capacity constraints.

---
### Page 3 — Demand & Product Behaviour
- Revenue versus Order Volume by Category
- Discount dependency analysis
- Comparison of AOVs for different product categories

**Key takeaway:** 
Demand is High-frequency and led by necessities, but over half of the orders are discounted, which may indicate promotion-led growth and risk to profitability.
---

### 📂 Datasets Used

| Dataset Name | Description |
|-------------|-------------|
| `fact_orders` | Order-level transactional data including delivery performance, order value, discounts, platform, category, city tier, and time-of-day information |
| `dim_products` | Product category reference data used for demand and value analysis |
| `dim_platforms` | Platform-level metadata representing major quick commerce players |
| `dim_cities` | City and metro-tier classification used for geographic analysis |
| `dim_dates` | Date reference table used for temporal aggregation and filtering |

---

### 📊 Data Provenance & Modelling Note

It is a **synthetic and analytically modelled** dataset, meant to reflect realistic patterns seen in industry reports and public benchmarks of:
- Platform-level demand concentration
- Metro and non-metro distribution
- Delivery-time variability under peak load
- Category-level demand frequency and basket value
- Discount-driven order behavior

Although it is not sourced from a single production system, the dataset is **structurally consistent with real operational data**.
Note that this project places more emphasis on **analytical reasoning, metric design, and business storytelling** rather than data collection.

---

## 🛠 Tools & Skills Used

- Power BI - DAX: measures, calculated columns 
- Data modelling & relationships 
- KPI design & Conditional Formatting 
- Market structure analysis 
- Operational diagnostics 
- Business Storytelling 

---

## 📌 Key Business Insights


- Despite general operational stress, market leadership exists.
- SLA breaches are systemic and peak-demand driven 
- The demand is frequency-led rather than value-led. 
- Reliance on heavy discounts raises sustainability and profitability concerns -
