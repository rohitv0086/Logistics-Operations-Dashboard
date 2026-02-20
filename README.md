# Logistics-Operations-Dashboard

Markdown

# 🚚 Logistics Operations Control Tower

## Project Overview
This project simulates a real-world logistics environment where I analyze **On-Time Delivery (OTD)** performance and identify **shipping bottlenecks**. The goal was to transform raw, messy operational data into an interactive dashboard for an Operations Manager.

## ⚠️ The Business Problem
- Raw data contained duplicate entries and formatting errors ("Dirty Data").
- No visibility into **Backlog Aging** (how long orders have been stuck).
- Impossible data entries (e.g., Ship Date < Order Date) were skewing reports.

## 🛠️ The Solution (Excel & Power Query)
I built an automated dashboard that:
1.  **Ingests Data:** Uses **Power Query** to pull raw data.
2.  **Cleans Data:** Automatically trims whitespace, removes duplicates, and standardizes date formats.
3.  **Validates Data:** Flags logical errors (like negative lead times) with a custom "Data Quality" alert system.
4.  **Visualizes KPIs:** Tracks SLA Breaches and Courier Performance.

## 📊 Key Insights Generated
- **Bottleneck Detection:** Identified that *BlueDart* had a 15% higher delay rate in the *North Region*.
- **Backlog Management:** Created an aging bucket (0-5 days, 5-10 days) to help teams prioritize old orders.

## 📷 Dashboard Preview
*(Upload your screenshot to the repo and paste the link here)*

## How to Use This File
1. Download the `.xlsx` file.
2. Go to the `Raw_Data` tab and add new rows.
3. Go to **Data -> Refresh All**.
4. Watch the Dashboard update automatically!
