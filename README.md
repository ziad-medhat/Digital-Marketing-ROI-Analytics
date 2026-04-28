# Digital-Marketing-ROI-Analytics
An end-to-end marketing analytics project analyzing campaign efficiency and Return on Investment (ROI). This project evaluates 900+ campaigns across organic, paid, and referral channels to identify high-performing strategies and optimize budget allocation.

# Marketing Campaign Performance & Advanced ROI Modeling

## 📌 Project Overview
This project is a technical deep-dive into **Marketing Data Engineering and Analytics**. Using a dataset of **931 cross-channel campaigns** (2022-2023), I developed a robust analytical engine in Microsoft Excel to evaluate campaign efficiency, normalize financial performance, and provide actionable business insights.

The focus of this project is the **Logic Layer**—transforming raw, disparate marketing data into a standardized model that accurately measures Return on Investment (ROI) and Revenue impact across diverse budgets and channels.

---

## 🛠️ Data Engineering & Technical Logic
I implemented a multi-stage data processing pipeline within Excel to move beyond surface-level metrics:

### 1. Data Cleaning & Standardization (ETL)
* **Dataset Size:** 931 unique campaign records.
* **Normalization:** Standardized naming conventions for channels (Organic, Paid, Promotion, Referral) and target audiences (B2B vs B2C).
* **Date Engineering:** Calculated campaign durations to analyze seasonal performance trends.

### 2. Advanced Financial Modeling (The "Brain" of the Project)
To ensure a fair comparison between campaigns with vastly different budgets, I built a custom logical framework using advanced Excel formulas:
* **Adjusted Revenue:** A calculated metric to smooth out financial outliers, providing a more realistic view of channel contribution.
* **Ratio Analysis:** Developed a custom efficiency ratio to measure the direct impact of every dollar spent.
* **ROI Normalization (0-1 Scale):** I applied a statistical normalization formula to the ROI column. This scales all performance data between 0 and 1, allowing stakeholders to identify "top-tier" campaigns regardless of the initial investment size.
* **Status Logic:** Implemented nested `IF` statements to automatically flag campaign performance as **"OK"** or **"Low Performing"** based on calculated ROI thresholds.

---

## 📊 Component Breakdown

### A. The Analytical Backend (Data Sheet)
This view highlights the complex formula work and data structure. It demonstrates my ability to manage large-scale data while maintaining strict logic for calculated columns.
* **Tools:** XLOOKUP, Data Validation, Logical Functions, Math & Trig Functions.

### B. The Performance Dashboard (Executive UI)
An interactive interface built to communicate insights to non-technical stakeholders.
* **Dynamic Slicers:** Connected to a unified Pivot Cache, allowing users to filter the entire report by **Year**, **Marketing Channel**, or **Target Audience**.
* **Trend Visualization:** Area and Bar charts tracking **Adjusted Revenue** and **ROI Ratios** over time.

### C. Key Business Findings
* **Revenue Impact:** The model tracked over **$332.9 Million** in total Adjusted Revenue.
* **ROI Trends:** Analysis reveals that **Paid Marketing** led 2022 performance (7.41 ROI), while **Organic** channels showed the highest efficiency growth in 2023.
* **Volume vs. Value:** While **Promotion** had the highest campaign count (251), the **Normalized ROI** revealed that smaller-scale Referral campaigns often yielded higher efficiency.

---

## 📂 Repository Structure
* `marketing_campaigns.xlsx`: The primary workbook containing the raw data, processing logic, and dashboard.
* `marketing_campaigns.csv`: A flat-file export of the processed data for auditing.
* `Screenshots/`: High-resolution captures of the data model and the final UI.

---

## 🚀 How to Audit This Model
1.  **Open the Excel File:** Navigate to the main data sheet to inspect the formula logic in the green-shaded columns.
2.  **Interact with Slicers:** Go to the Dashboard tab and use the filters. Observe how the Pivot Tables and Charts update instantly to reflect the filtered segments.
3.  **Review the Pivot Layer:** Inspect the hidden or secondary sheets to see how the data is aggregated to drive the visualizations.

---

## 📈 Visual Documentation

### I. Data Engineering & Model Logic
*Evidence of the backend processing and custom formula implementation.*
![Data Logic & Formulas](Screenshot%202026-04-28%20025212.png)
![2](Screenshot%202026-04-28%20025133.png)

### II. Interactive Performance Dashboard
*The final executive-level summary for business decision-making.*
![Executive Dashboard](Screenshot%202025-08-22%20172110%20(1).png)

---
*Developed by [Your Name/Profile] as part of a professional Data Analytics portfolio.*
