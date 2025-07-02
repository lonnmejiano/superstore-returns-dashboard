![superstore-return-1200x400](https://github.com/user-attachments/assets/1e634f3b-4aae-44b5-9f0a-627acda6bfd9)




## Overview
This project presents an interactive **Tableau dashboard** that analyzes return patterns at SuperStore, with the goal of uncovering trends, pinpointing problem categories, and informing executive decisions on logistics and sales strategies.

By comparing return rates against total sales across product categories, regions, and timeframes, the dashboard highlights key factors contributing to customer dissatisfaction and unnecessary revenue loss.

---

## 🎯 Objectives
- Identify high-return product categories and regions
- Analyze seasonal trends and monthly return fluctuations
- Visualize dual-axis metrics for return rates vs. revenue
- Provide actionable insights for operations and executive teams

---

## 📊 Dataset
The dataset includes SuperStore sales and returns information:
- `Order ID`, `Product Name`, `Category`, `Sub-Category`
- `Sales`, `Quantity`, `Profit`
- `Order Date`, `Region`, `Returned (Yes/No)`
- Cleaned and joined using a **LEFT JOIN** on Returns table

---

## 📈 Key Metrics
- **Return Rate** = `SUM(Returned) / COUNT(Order ID)`
- **Total Returns** = `SUM(Returned)`
- **Revenue Impact** = Lost sales or low-profit segments with high return ratios

---

## 🛠️ Tools Used
- **Tableau** – Interactive dashboards, dual-axis visualizations, return maps
- **Excel** – Data preprocessing, calculated fields, conditional formatting
- **SQL (optional)** – Data joins and cleansing (LEFT JOIN to link Returns table)

---

## 📌 Visual Features
- 🔄 **Dual-Axis Chart** – Return Rate vs. Sales by Month
- 🌍 **Map Visualization** – Geographic return trends by state or region
- 📊 **Category Breakdown** – High-return product categories
- 📆 **Time-Series Trends** – Monthly return spikes

---

## 📸 Sample Screenshots

![Dual-Axis-Chart](https://github.com/user-attachments/assets/b63c95d6-92fd-4205-af50-78f95da3f668)
*Monthly Sales vs. Return Rate*

![Return-Rate-Category](https://github.com/user-attachments/assets/840f0280-20b0-4417-84eb-8455e71be57b)
*Sub-categories with the highest return rates*

![Geographical-Map](https://github.com/user-attachments/assets/e17f2832-eb2e-4387-a0f6-fc98e74f57a3)

*Regional distribution of returns*

---

## 📌Strategic Recommendation

Based on the return trends uncovered in this analysis, the following actions are recommended:

- 📦 **Optimize Inventory for High-Return Categories**: Focus on improving quality or supplier standards for Office Supplies and Technology sub-categories with above-average return rates.
- 📉 **Implement Seasonal Promotions Strategically**: Monthly spikes in returns post-Q4 suggest a need for better customer education during seasonal surges and clearer return policies.
- 🌍 **Reevaluate Logistics in High-Return Regions**: Regional patterns (e.g., higher returns in the South) indicate a need for deeper review of shipping practices or warehouse handling.
- 💬 **Develop Customer Feedback Loops**: Establish post-return surveys to capture qualitative feedback and reduce future return triggers.

These targeted strategies can reduce return volume, preserve profit margins, and enhance customer satisfaction.

