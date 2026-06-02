# 📂 SQL Projects

> [← Back to Portfolio](../README.md)

---

## Project 1: Sales Performance Analysis
*Tech:* PostgreSQL, Window Functions, CTE

- **Goal:** Calculate monthly rolling revenue, customer retention rate, and year-over-year growth.
- **Highlights:**
  - Used `ROW_NUMBER()` and `LAG()` to compare period-over-period metrics.
  - Built a materialized view for fast dashboard queries.
- **Status:** ✅ Completed

---

## Project 2: ETL Pipeline for Marketing Data
*Tech:* MySQL, Python (pandas), cron

- **Goal:** Automate ingestion of CSV exports from Google Ads and Facebook Ads into a staging database.
- **Highlights:**
  - Schema design with `STAGING`, `CLEAN`, and `MART` layers.
  - Incremental load logic using `MAX(load_timestamp)`.
- **Status:** 🛠 In Progress

---

## Project 3: Customer Segmentation (RFM)
*Tech:* PostgreSQL, SQL Window Functions

- **Goal:** Segment customers into Recency‑Frequency‑Monetary groups.
- **Highlights:**
  - `NTILE(4)` to assign quartile scores.
  - Final segments: Champions, Loyal, At Risk, Lost.
- **Status:** 📝 Planned

---

*More projects will be listed here as they are added.*
