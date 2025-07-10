# 🚚 Power BI Dashboard – Logistics Performance & Monitoring

This project presents an interactive Power BI dashboard that tracks and analyzes key logistics KPIs such as delivery performance, fuel efficiency, supplier reliability, and risk classification. The dashboard empowers stakeholders to optimize operations and make data-backed decisions using real-time metrics.

---

## 📦 Project Overview

- **Tool Used**: Microsoft Power BI  
- **File Type**: `.pbix`  
- **Dashboard Name**: `logistics project.pbix`  
- **Data Refresh**: Automated via **Microsoft Power Automate**

---

## 🎯 Objectives

- Monitor delivery status and route efficiency  
- Analyze fuel cost trends and average consumption  
- Evaluate supplier performance and reliability  
- Assess operational risk by classification  
- Enable timely decisions with scheduled data updates

---

## 🧹 Data Preparation

- Cleaned and transformed >10,000 records using **Power Query Editor**  
- Removed nulls, corrected data types, and standardized field formats  
- Created calculated measures for:
  - **On-Time Delivery Rate**: `% of orders delivered on or before expected date`
  - **Average Fuel Cost/km**: `Total Fuel Spend / Total Distance`
  - **Supplier Reliability Score**
  - **Risk Impact Classification**

---

## 🔄 Data Refresh & Automation

- **Microsoft Power Automate** is used to:
  - **Schedule daily data refreshes** for the dashboard  
  - **Send automated email alerts** if the refresh fails  
  - Ensure data availability with minimal manual intervention  
- Connected to Excel Online or Google Sheets as dynamic data sources

---

## 📊 Dashboard Highlights

| Section                  | Description |
|--------------------------|-------------|
| **KPI Overview**         | On-Time Rate, Avg Fuel Rate, Supplier Reliability, Risk Breakdown |
| **Delivery Tracker**     | Visual map and bar chart of delivery status by region |
| **Fuel Consumption**     | Trend chart of average fuel usage per km |
| **Supplier Analysis**    | Scorecards ranking suppliers by performance |
| **Risk Dashboard**       | High-risk shipments by category, impact, and geography |
| **Filters**              | Date, region, supplier, vehicle type, and more |

---

## 📈 Key Metrics Tracked

- On-Time Delivery Rate (%)  
- Average Fuel Cost per Kilometer (₹)  
- Supplier Reliability (%)  
- Risk Classification (Low/Medium/High)  
- Congestion Index, Vehicle Usage Rate  
- Delivery Delays and Failure Reasons  

---

## 🚀 Future Enhancements

- Integrate real-time **GPS tracking APIs** for live delivery monitoring  
- Add **predictive analytics** to forecast delays or supply chain disruptions  
- Implement **anomaly detection** for outlier shipments  
- Publish to **Power BI Service** with access control for different teams  
- Export summary reports to **PDF or Excel** via Power Automate  

---

## 🙏 Acknowledgements

- Internal logistics dataset for performance benchmarking  
- Microsoft Docs and Power BI community for DAX guidance  
- Power Automate templates for scheduled refresh & failure alert workflows

---

## 📬 Contact

Created by: **Harshavardhan Reddy Chamakura**  
📧 Email: chamakharsha10@gmail.com  

