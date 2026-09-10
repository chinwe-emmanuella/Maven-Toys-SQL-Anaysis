# Maven Toys Sales & Inventory SQL Analysis

## Project Overview
This repository contains a relational database capstone project analyzing sales and inventory metrics for **Maven Toys**, a toy store chain in Mexico. Using **PostgreSQL**, the objective was to write structured database queries to uncover critical business insights regarding product profitability, inventory valuation, and stockout impacts for the management team.

## 📊 Core Business Questions & Insights

### Q1: What are the business's profit drivers? Is this the same across store locations?
* **Top Profit Categories:** **Toys** is the absolute highest total profit driver overall ($1,079,527.00), followed closely by **Electronics** ($1,001,437.00). However, **Electronics** has a much higher margin efficiency of **44.6%** compared to Toys at **21.2%**.
* **Store Location Variations:** Drivers change by city market. For example, **Electronics** dominates profits in **Aguascalientes** ($19,619.00), while **Toys** takes the lead in **Campeche** ($34,152.00).

### Q2: How much money is tied up in inventory at the toy stores?
The query joins the inventory and products tables to aggregate total physical units on hand and calculate the exact financial capital locked up in assets.

#### 📦 Inventory Valuation Breakdown

| Product Category | Total Units in Stock | Total Inventory Value |
| :--- | :--- | :--- |
| **Toys** | 7,553 | $99,861.47 |
| **Art & Crafts** | 8,635 | $65,075.55 |
| **Sports & Outdoors** | 4,181 | $53,077.19 |
| **Games** | 4,115 | $51,489.45 |
| **Electronics** | 2,418 | $30,705.82 |

#### 💡 Executive Insights
* **Highest Capital Investment:** The most capital is tied up in the **Toys** category with an inventory value of **$99,861.47**, representing the highest stock risk for the business.
* **Lowest Capital Investment:** **Electronics** holds the lowest amount of tied-up cash at **$30,705.82**, matching its lower unit count (2,418 units).

---

## 🛠️ Technical SQL Skills Demonstrated
* **Relational Joins:** Connecting products, stores, inventory levels, and transaction tables (`INNER JOIN`, `LEFT JOIN`).
* **Data Aggregation & Grouping:** Using `SUM()`, `COUNT()`, `AVG()`, and `GROUP BY` to structure metrics by store and category.
* **Analytical Computations:** Creating calculated metrics for inventory value and runway timelines.

## 📂 Project Materials
* **Analysis Report:** Detailed query scripts, code execution snapshots, and data interpretations are fully documented in the uploaded project PDF file.
*
