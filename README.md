# Ferns and Petals (FNP) Sales Analysis Dashboard


## 📌 Project Overview

This project focuses on analyzing a comprehensive sales dataset from **Ferns and Petals (FNP)**, a premier gifting brand specializing in major occasions like Diwali, Raksha Bandhan, Holi, Valentine's Day, Birthdays, and Anniversaries. 

Using **Advanced Microsoft Excel**, I built an interactive data dashboard to uncover critical insights regarding sales trends, seasonal fluctuations, customer spending behavior, and product performance. 

The primary objective was to transform raw order data into actionable business intelligence to help optimize marketing strategies, streamline delivery operations, and maximize product revenue.


---


## 🛠️ Tech Stack & Architecture

Instead of traditional Excel sheets, this project utilizes Excel's robust **Business Intelligence (BI) stack** to handle complex data relationships efficiently:

* **Power Query:** Used for ETL (Extract, Transform, Load) processes—cleaning the raw dataset, handling null values, establishing correct date/time formats, and creating custom columns for delivery windows.

* **Excel Data Model & Power Pivot:** Developed a relational data schema connecting product, order, customer, and date details. This eliminated the need for heavy `VLOOKUP` or `XLOOKUP` formulas, significantly optimizing workbook performance.

* **DAX (Data Analysis Expressions):** Written to calculate key business metrics and KPIs dynamically across different filter contexts.


---


## 📊 Key Metrics (KPIs)

* **Total Orders:** 1,000 orders

* **Total Revenue:** ₹35,20,984.00

* **Average Order to Delivery Time:** 5.53 days

* **Average Customer Spend:** ₹3,520.98


---


## 📈 Executive Summary & Business Insights


### 1. Seasonal Trends & Occasion Drivers

* **Peak Months:** Revenue experiences massive spikes in **February** (driven heavily by Valentine's Day and Anniversaries) and **August** (driven by Raksha Bandhan). 

* **Revenue by Occasion:** **Anniversaries** and **Raksha Bandhan** emerge as the top two revenue-generating occasions, both crossing the ₹6,00,000 threshold individually. 

* **Low Seasons:** Post-February (April–July) and post-August (September–October) showcase significant dips in sales, highlighting opportunities for targeted off-season promotional campaigns.


### 2. Product Performance

* **Top Product Categories:** The **"Colors"** category is the undisputed leader, generating over ₹10,00,000 in revenue. **Soft Toys** and **Sweets** also show robust performance, both exceeding ₹7,00,000.

* **Top 5 Individual Products:** **Magnam Set** leads individual product revenues (crossing ₹1,20,000), followed closely by **Quia Gift**, **Dolores Gift**, **Harum Pack**, and **Deserunt Box**.


### 3. Customer & Hourly Ordering Behavior

* **Hourly Order Activity:** Ordering activity exhibits a clear bimodal distribution during the day. Peak ordering hours occur mid-morning around **6:00 AM** and surge to their highest daily levels in the evening between **6:00 PM and 7:00 PM**.

* **Geographic Distribution (Top Cities):** Demand is highly decentralized across Tier-2 and Tier-3 cities. **Dhanbad** and **Imphal** lead the chart with the highest volume of orders (~28-29 orders each), followed closely by **Kavali** and **Haridwar**.
