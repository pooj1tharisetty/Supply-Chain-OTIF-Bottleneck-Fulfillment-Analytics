# Supply-Chain-OTIF-Bottleneck-Fulfillment-Analytics

Supply Chain OTIF Analytics & Business Intelligence

An end-to-end data engineering and business analytics project evaluating **On-Time In-Full (OTIF)** fulfillment performance, carrier SLAs, and regional revenue risks using **Quadratic**, **PostgreSQL (Supabase)**, and **Python (Pandas/Plotly)**.

---

## 📌 Executive Summary
Analyzing 58,136 global order records revealed that delivery delays (**41.38% On-Time Rate**), rather than stockouts (**97.78% Fill Rate**), drive a critically low baseline **OTIF Rate of 40.24%**. Over **$2.3M in revenue is at risk** across Western Europe and Central America due to delivery bottlenecks.

---

## 🛠️ Tech Stack & Architecture
* **Business Analysis & Grid Modeling:** Quadratic
* **Database & Warehousing:** PostgreSQL (Supabase)
* **Data Processing & Analytics:** Python (Pandas)
* **Data Visualization:** Plotly Express (Google Colab)

---

## 📊 Visual Dashboards & Insights

<img width="1917" height="1078" alt="Screenshot 2026-07-28 132704" src="https://github.com/user-attachments/assets/80898275-5389-45c9-84a5-3fdcd01250dc" />
<img width="1917" height="866" alt="Screenshot 2026-07-27 193807" src="https://github.com/user-attachments/assets/3d639aff-e40b-4007-bdb8-d25c83e70fb6" />



---

## 💡 Key Findings & SQL Analysis
1. **Shipping SLA Breach:** First Class shipping records a 100% SLA failure rate due to unrealistic 1-day delivery schedules.
2. **Regional Revenue Exposure:** Western Europe ($1.2M) and Central America ($1.1M) carry the highest financial risk from fulfillment delays.
3. **Category Risk:** High-value categories like *Women's Golf (6.08%)* exhibit elevated cancellation and fraud rates.

---

## 📁 Repository Contents
* `DataCo_Supply_Chain_OTIF_Analysis_Report.pdf` - Full executive PDF report
* `supply_chain_analysis.ipynb` - Interactive Google Colab notebook with SQL & Plotly code
* `dataco_clean_otif.csv` - Cleaned 58k-row dataset
* `visuals/` - Rendered dashboard chart previews
