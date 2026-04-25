# 📊 Supply Chain & Supplier Performance Analytics | Power BI

## 🎯 Project Overview
This project is an end-to-end data analytics solution designed to evaluate supply chain efficiency, measure supplier performance, and assess the accuracy of demand prediction models. By transforming raw procurement data into interactive Power BI dashboards, this project uncovers hidden costs and operational bottlenecks.

## 💡 Key Business Insights Discovered
During the analysis, several critical insights were extracted using advanced DAX modeling:
* **The Cost of Human Intervention:** Developed a Forecast Value Added (FVA) metric which revealed that manual overrides to the AI/baseline predictions resulted in **12,000 additional units of error** (-12K FVA).
* **Supplier Hidden Costs:** Created a custom Total Cost of Ownership (TCO) model calculating the financial impact of Supplier Lead Time Variability (Safety Stock) and Quality Incident Rates (Blocked Inventory).
* **Delivery Reliability:** Evaluated suppliers based on strict **OTIF (On-Time In-Full)** standards, separating logistical delays from production shortages.

## 🛠️ Technical Skills & Tools Showcased
* **Data Visualization:** Power BI (Scatter Plots, Radar Charts, Dynamic Smart Narratives, Matrix Hierarchies).
* **DAX Formulas:** Complex measure creation for WAPE (Forecast Accuracy), Coefficient of Variation (Volatility), and dynamic labeling.
* **Data Modeling:** Star schema design and relationship management.
* **Core Tech Stack:** Power BI, DAX.

## 📸 Dashboard Snapshots

<img width="1353" height="763" alt="image" src="https://github.com/user-attachments/assets/1d60aae3-bb52-41cd-8d84-0744a0cfb4a3" />
<img width="1349" height="764" alt="image" src="https://github.com/user-attachments/assets/f97bbcc1-8e1e-4ef8-a54c-ca7521e335dc" />


### 1. Supplier Sourcing Strategy & Hidden Costs
<img width="1352" height="766" alt="image" src="https://github.com/user-attachments/assets/c084c52c-4ba7-477a-9673-720e143484ed" />

*Scatter plot analyzing the trade-off between OTIF reliability and hidden supply chain costs.*

### 2. Demand Forecast Accuracy & Volatility
<img width="1358" height="767" alt="image" src="https://github.com/user-attachments/assets/13762271-40e1-4f21-a7af-21a836addb4f" />
*Evaluating machine prediction vs. actual consumption and human error.*

## 🚀 How to Interact with this Project
1. Download the `Aerospace Supply Chain Performance & Forecasting.pbix` file from this repository.
2. Open it using Power BI Desktop.
3. Explore the dynamic filters, tooltips, and the custom Smart Narrative features.

