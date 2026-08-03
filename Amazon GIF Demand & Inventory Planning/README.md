# 📦 Amazon Great Indian Festival (GIF) Peak Demand & Inventory Optimization Model

## Executive Summary
This project delivers a comprehensive end-to-end inventory planning and last-mile capacity model for a **14-day Great Indian Festival (GIF) peak surge**. Handling a portfolio of **30 core SKUs**, the model balances safety stock levels, reorder thresholds, and working capital risk while evaluating last-mile delivery station throughput under peak package surges (up to 34,000 daily packages).

---

## 📊 Key Business & Operational Metrics
* **Total Expected Peak Demand:** **74,700 Units**
* **Total Inventory Capital at Risk:** **₹2,25,03,500** (*Critical / Reorder SKUs*)
* **Stock Health Index %:** **50.0%** (*15 Healthy / 15 At Risk or Overstocked*)
* **Total Replenishment Orders Required:** **24,574 Units**

---

## 🛠️ Model Architecture & Methodology
1. **Safety Stock Calculation:** Formulated using dynamic lead times and lead time variability buffers (Daily Demand x Lead Time x 0.4)
2. **Reorder Point (ROP):** Automated reorder triggers based on burn rates during peak demand windows.
3. **Last Mile Capacity Planning:** Evaluates daily station throughput across **3 iteration versions** (Initial, Optimized, Final) with custom buffer percentages (8% - 10%) to avoid hub backlogs.

---

## 📂 Repository Contents
* `Amazon_Peak_Inventory Planning.xlsx`: Complete Excel workbook with live formulas, dynamic KPI cards, and capacity planning iterations.
