# 🛒 US Superstore Sales Analysis

![Project Status](https://img.shields.io/badge/Status-Completed-success) ![Tool](https://img.shields.io/badge/Tool-Power%20BI-yellow)

### 🚀 Project Overview
This project is a professional-grade Business Intelligence dashboard designed to analyze sales and profitability for a US-based retail superstore. The goal was to transform raw transaction data into actionable insights, focusing on identifying profit "leaks" and high-performing regions.

> **Live Dashboard:** [Link to .pbix file or online demo if you have one]

---

### 📸 The Dashboard

![US Superstore Dashboard](powerbi-screenshot.png)
*(Note: This dashboard features a modern "Grid Layout" design for intuitive navigation and data consumption.)*

---

### 💼 Business Scenario (The Problem)
**Role:** Junior Data Analyst
**Stakeholder:** Regional Sales Manager
**The Challenge:**
The company is experiencing high sales volume ($2.3M) but disproportionately low profit margins in specific categories. Management requires a clear, interactive tool to answer:
1.  **Profitability:** Which products are driving revenue but losing money?
2.  **Geography:** Where are our strongest and weakest markets?
3.  **Trends:** How is performance trending year-over-year?

---

### 🔍 Key Insights & Findings

* 🔴 **The "Table" Crisis:** Despite generating significant revenue, the **Tables** sub-category is the primary source of financial loss (shown in clear Red on the dashboard). This indicates a critical pricing or shipping cost issue.
* 🔵 **Tech Dominance:** **Phones** and **Copiers** are the highest-margin items.
* 🌍 **Geographic Strategy:** The grayscale map highlights that while the East Coast has high density, specific states in the Central region are underperforming in profit despite high sales volume.
* 📉 **Discount Impact:** An analysis of the "Discount" KPI suggests that heavy discounting in the Furniture category is eroding margins.

---

### 🛠️ Technical Implementation

**1. Data Modeling & Transformation (Power Query)**
* Cleaned raw data, fixed currency data types, and removed null values.
* Created a **Star Schema** to optimize performance.

**2. Advanced DAX Measures**
* Calculated `Total Sales`, `Total Profit`, `Profit Margin %`, and `YoY Growth`.
* Created dynamic measures for the KPI cards to respond to slicer selection.

**3. UI/UX Design (The "Pro" Touch)**
* **Grid Layout:** Implemented a structured 3-column layout (KPIs | Visuals | Filters) for maximum readability.
* **Conditional Formatting:** Used a strict "Blue (Positive) / Red (Negative)" logic to instantly flag underperformance.
* **Visual Hierarchy:** Used a grayscale map to ensure data points pop, and containerized visuals with shadows to create depth.

---

### 🚀 Strategic Recommendations

Based on this analysis, I recommend the following actions:
1.  **Immediate Audit of "Tables":** Stop all discounts on Tables and renegotiate shipping rates for this heavy category.
2.  **Focus Marketing on "Technology":** Shift ad spend towards Phones and Copiers to maximize high-margin sales.
3.  **Regional Pricing:** Implement region-specific pricing strategies for the Central US to recover profitability.

---

*Created by Georlia Sgouraki - Aspiring Data Analyst*
