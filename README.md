# 📊 Olist Brazil E-Commerce Data Analytics Project

## 📌 Executive Summary
This project delivers an end-to-end analytical evaluation of Olist Brazil's e-commerce dataset using **BigQuery SQL**, **Google Sheets**, and **Data Visualization**. The primary goal is to uncover revenue drivers, diagnose seasonal anomalies, evaluate Average Order Value (AOV) dynamics, and optimize checkout infrastructure.

---

## 🛠️ Tech Stack & Business Frameworks
* **SQL Engine:** BigQuery (Advanced Aggregations, Inner Joins, Date Extraction, Filtering)
* **Spreadsheet Analytics:** Google Sheets (Pivot Tables, Dual-Axis Charts, Pareto Analysis, Percentage Formulas)
* **Presentation:** Executive Slide Deck
* **Business Frameworks:** Pareto 80/20 Rule, Month-on-Month Trend Analysis, AOV Elasticity, Payment Gateway Redundancy

---

## 📁 Repository Structure
├── DATA_ANALYSIS_Brazil_Ecommerce.pdf # Executive Slide Deck
├── queries.sql                        # BigQuery SQL Scripts
├── data/                              # Aggregated CSV Outputs
└── README.md                          # Project Documentation

---

## 🚀 Key Project Tracks & Business Insights

### 🔹 Track 1: Month-on-Month Revenue & Volume Trends
* **Finding:** September hit annual peak revenue and order volume, followed by a >50% crash in October post price adjustment.
* **Data Anomaly:** February and October exhibited identical bar heights for volume and revenue despite unit price hikes, signaling potential volume inflation or revenue logging distortion.
* **Action:** Immediate transaction-level audit recommended prior to Q4 reporting.

### 🔹 Track 2: Product Revenue Drivers (Pareto 80/20 Rule)
* **Finding:** Out of 26 product categories, the top 14 (e.g., Outerwear & Coats, Jeans, Sweaters) generate **80.76% of total gross merchandise value**.
* **Action:** Enforce strict zero-stockout inventory priority and strict quality control for top 14 SKUs.

### 🔹 Track 3: Average Order Value (AOV) Dynamics
* **Finding:** Monthly AOV remains flat in a narrow band ($58–$61). The September revenue surge was purely order-volume driven, not basket-expansion driven.
* **Action:** Pivot strategy toward AOV expansion via product bundling, minimum spend free-shipping thresholds, and cross-sell checkout prompts.

### 🔹 Track 4: Payment Gateway Distribution & Reliability
* **Finding:** Credit Cards dominate with **78.34% revenue share** and **73.92% transaction frequency**, followed by Boleto (17.92%).
* **Action:** Implement multi-gateway server redundancy for credit card processing and auto-retry prompts to alternative methods (Boleto/Debit) on decline.

---

### 📊 Live Links & Presentation Deck
* 📄 **Google Presentation Deck:** [View Executive Slides](https://docs.google.com/presentation/d/1tMl1ISkXbQN9mVzTkOmvEe_BWNonEOhrEc0_h3l_fyM/edit?usp=sharing)
* 📊 **Google Sheets Analysis:** [View Live Google Sheet]([YOUR_GOOGLE_SHEET_LINK_HERE](https://docs.google.com/spreadsheets/d/1pR5gn_gw_zQlVzZEo62o_lGroHMIWXWixGxNJD1jpAw/edit?usp=sharing))
