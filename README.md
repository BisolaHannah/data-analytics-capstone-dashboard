# Data-Analytics-Capstone-Project

## 📌 Executive Summary (TL;DR)
This project analyzes a 2020 operational data using Microsoft Excel to track core business metrics and optimize performance. By designing an interactive dashboard featuring dynamic **KPI Cards** and interactive slicers, stakeholders can monitor real-time company health at a glance. The final dashboard successfully uncovers regional trends and product line inefficiencies, driving data-backed recommendations for the executive board.

* **Tools Used:** Microsoft Excel (Advanced Pivot Tables, Pivot Charts, Slicers, XLOOKUP, Conditional Formatting)
* **Key Methodologies:** Data Cleaning & Transformation, Descriptive Analytics, Dashboard Architecture

---

## 💼 The Business Problem
The executive board needed a more transparent and data-driven view of sales performance. They want to understand customer demand trends, product category growth, and producer contributions. Prior to this project, data was siloed in massive, messy spreadsheets, making it incredibly time-consuming for leadership to spot underperforming metrics or track growth efficiently. 

This project solves that by creating a single source of truth dashboard for daily operational decision-making, transforming raw data rows into instant, visual insights.

---

## 📊 Dashboard Features & Technical Execution

### 1. High-Impact KPI Cards
Designed and implemented a dedicated KPI section at the very top of the dashboard to surface immediate macro-level insights for C-suite executives.
* **Metrics Tracked:** Total Revenue, Total Units Sold, Average Order Value, And Top Selling Brand
* **Technical Setup:** Built using dynamic Pivot Tables linked via custom formulas to prevent chart breakage, styled with clean conditional formatting to highlight performance targets vs. deficits.

### 2. Interactive Data Filtering & Segmentation
To ensure the dashboard is entirely user-friendly for non-technical stakeholders, I integrated cross-filtering components.
* **Dynamic Slicers & Timelines:** Allowed users to instantly filter the entire dashboard by order channel, category, producer, customer type with a single click.
* **Data Hygiene:** Cleaned the underlying dataset by removing duplicates, handling missing null values, and standardizing date formats before building the visuals.
* **Created a link for each chart and inserted it into the dashboard for easy reference.
---

## 📈 Key Insights & Strategic Recommendations
Based on the dashboard trends, the following strategic insights were presented to the board:

* **Identify High-Performing Sectors:** The dashboard clearly highlighted that Mobile App and WhatsApp dominate sales, signaling a clear area to scale operations.
* **Address Underperforming Segments:** The KPI cards flagged a consecutive month-over-month dip in Hamyat Kimya Nigeria Limited in the producer segmentation, Alhaja in customer segmentation, Butter in the Top selling products, triggering an operational review.
* **Actionable Next Step:** Reallocate underutilized marketing and operational resources from lower-performing channels into the top sectors highlighted by the dashboard visuals.

---

## 📁 Repository Structure
* `/data`: Contains the anonymized raw dataset used for this analysis.
* `/dashboard`: Houses the final `.xlsx` workbook featuring the interactive dashboard.
* `README.md`: Project summary and methodology documentation.

---
*Disclaimer: All sensitive company information has been anonymized, and numbers have been scaled to protect data privacy.*
