# 🚀 **Techtronix Power BI Capstone Project**

## 🧭 **Table of Contents**
1. [📖 Overview](#overview)  
2. [🎯 Project Objectives](#project-objectives)  
3. [🧰 Tools and Technologies Used](#tools-and-technologies-used)  
4. [📊 Data Overview](#data-overview)  
5. [🧹 Data Cleaning and Transformation](#data-cleaning-and-transformation)  
6. [🧩 Data Modeling](#data-modeling)  
7. [📈 Key Metrics and Insights](#key-metrics-and-insights)  
8. [💡 Business Impact and Recommendations](#business-impact-and-recommendations)  
9. [🔮 Future Enhancements](#future-enhancements)  
10. [👤 Project Owner](#project-owner)  

---

## 📖 **Overview**
The **Techtronix Power BI Capstone Project** is a comprehensive **business intelligence solution** developed to analyze the company’s **2023 transactional data** across product categories, customer sectors, and global regions.  

This project integrates twelve months of CSV-based sales data into a unified **Power BI dashboard**, providing **actionable insights** into **sales performance, profitability, and market distribution**.  

By combining automated data cleaning, dynamic DAX measures, and interactive visuals, the dashboard empowers decision-makers to **monitor performance**, **identify growth opportunities**, and **enhance operational efficiency**.

---

## 🎯 **Project Objectives**
- 📊 Build an end-to-end **Power BI analytics solution** to track sales, cost, and profit performance.  
- 🧾 Consolidate **monthly transaction data** (January – December 2023) into a unified dataset.  
- 🌍 Evaluate performance across **regions, product categories, and customer sectors**.  
- 🏆 Identify **high-value customers** and **top-performing product lines**.  
- 🔍 Provide an interactive platform for executives to **visualize KPIs and trends in real time**.  
- 💼 Support **data-driven decision-making** with profitability and sales insights.

---

## 🧰 **Tools and Technologies Used**
| 🧠 Tool / Technology | ⚙️ Purpose |
|-----------------------|-------------|
| **Microsoft Power BI** | Data visualization, reporting, and dashboard development |
| **Power Query Editor** | Data extraction, transformation, and loading (ETL) |
| **DAX (Data Analysis Expressions)** | Creation of calculated measures and KPIs |
| **CSV / Microsoft Excel** | Raw data sources (monthly transaction files) |
| **Power BI Service** | Online publishing and collaboration |
| **PDF Reporting** | Final project documentation and presentations |

---

## 📊 **Data Overview**
The dataset includes **12 monthly CSV files** representing Techtronix’s **transactional records for 2023**.  
Each file captures sales and profitability details across multiple regions and product lines.  

| 🏷️ Field | 📋 Description |
|-----------|----------------|
| **TransactionID** | Unique identifier for each transaction |
| **Date** | Date of sale |
| **ProductID / ProductName / Category** | Product details |
| **QuantitySold** | Units sold per transaction |
| **UnitPrice** | Sale price per unit |
| **ProductionCost** | Cost incurred per unit |
| **TotalSaleAmount** | Total revenue generated |
| **Profit** | Revenue minus cost |
| **CustomerID / CustomerName** | Customer information |
| **CustomerSector** | Business, Automotive, or Consumer |
| **Country / Region** | Market classification |

🌍 **Regions Covered:** North America, Europe, and Asia-Pacific  
🏭 **Product Lines:** Microchip, Robotics, Sensor

---

## 🧹 **Data Cleaning and Transformation**
All preprocessing was performed in **Power Query** to ensure data consistency and reliability.  
Key transformation steps:  
- 🧩 Consolidated all monthly CSV files into one dataset.  
- 🔠 Standardized column headers and formats.  
- 🧼 Removed null, duplicate, and inconsistent entries.  
- 💰 Added calculated columns for *Total Sales* and *Profit Margin*.  
- 📅 Formatted date fields and mapped regional data for uniformity.  
- ⚡ Loaded the cleaned dataset into Power BI for modeling and analysis.

---

## 🧩 **Data Modeling**
The model follows a **Star Schema** design for performance and scalability.

- 📦 **Fact Table:** Transactional Sales Data  
- 🧭 **Dimension Tables:** Product, Customer, Region, Date  

**Relationships** were established between dimensions and the fact table to support dynamic slicing and filtering.  
Custom **DAX measures** developed include:
- 💵 *Total Sales* = SUM([TotalSaleAmount])  
- 💹 *Total Profit* = SUM([Profit])  
- 📊 *Profit Margin* = DIVIDE([Total Profit], [Total Sales])  
- 📆 *YTD Sales and Profit*  
- 🧮 *Top Product and Customer Rankings*  

---

## 📈 **Key Metrics and Insights**
✨ The dashboard uncovered key business insights:
- 💸 **Total Sales** and **Profit Margin** improved consistently quarter-over-quarter.  
- 🤖 **Robotics** achieved the **highest annual profit margin**, surpassing Microchips and Sensors.  
- 🌎 **North America** generated the highest revenue, while **Asia-Pacific** posted the **fastest growth rate**.  
- 🏭 **Industrial customers** led in volume and profitability.  
- 📅 **Q3 2023** recorded the strongest overall performance.

---

## 💡 **Business Impact and Recommendations**
This Power BI solution enabled the Techtronix management team to:
- 🔍 Monitor **monthly and quarterly performance trends**.  
- 📊 Identify **top-performing regions and product lines**.  
- 📈 Forecast **growth opportunities** using data patterns.  
- ⚙️ Optimize decision-making through **evidence-based insights**.  

**Recommendations:**
1. 🌏 Expand into **Asia-Pacific** markets showing high potential.  
2. 💰 Optimize **production costs** for Microchip products.  
3. 🤝 Strengthen relationships with **high-value industrial clients**.  
4. 🔄 Maintain quarterly data refreshes to ensure trend visibility.

---

## 🔮 **Future Enhancements**
- 🧠 Integrate **forecasting and predictive analytics** for sales projections.  
- ⏱️ Enable **real-time data refresh** via Power BI Gateway.  
- 🏗️ Extend the model with **inventory and logistics data**.  
- 🔔 Implement **automated alerts** for KPI thresholds and anomalies.

---

## 👤 **Project Owner**
**👨‍💼 Presented by:** [Nureni Tijani](https://github.com/NureniTijani)  
**📍 Location:** United States  
**🏗️ Project:** Techtronix Power BI Capstone Project  
**🧰 Tools:** Power BI | Power Query | DAX | Excel | PDF Reporting  
