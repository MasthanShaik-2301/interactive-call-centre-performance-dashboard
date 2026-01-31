# 🟦 Interactive Call Center Agent Performance Dashboard (Excel)

An interactive Excel dashboard that analyzes and ranks call-center agents (R01–R05) using key performance metrics such as calls handled, purchase amount, call duration, and customer satisfaction, enabling quick and data-driven operational decisions.

---

## 📌 Overview

This project focuses on analyzing call center operations data to evaluate **agent performance, customer behavior, and revenue contribution**.  
Using Excel PivotTables, slicers, and dynamic visuals, the dashboard allows users to interactively explore performance metrics and instantly compare agents across multiple dimensions.

The solution is designed to simulate a **real-world business reporting dashboard** used by operations managers and leadership teams.

---

## 📁 Project Structure
```bash
interactive-call-center-performance-dashboard/
├── Data/
   └── call_centre_data.xlsx         # raw transactions (calls)
├── images/
   ├── Rep01.png
   ├── Rep02.png
   ├── Rep03.png
   ├── Rep04.png
   └── Rep05.png
├── pivots_and_dashboard/
   └── Call_Center_Dashboard.xlsx    # data + Pivot sheets + interactive dashboard
└── LICENSE
```

## 🎯 Business Objective

The primary objectives of this project are to:
- Measure and compare call-center agent performance
- Rank agents based on overall contribution and efficiency
- Identify top-performing and underperforming agents
- Analyze customer satisfaction and purchasing behavior
- Support staffing, incentive, and training decisions

---

## 📊 Dataset Description

The analysis is based on call-level transactional data containing:
- Call Number and Customer ID  
- Call Duration and Date of Call  
- Representative (R01–R05)  
- Purchase Amount  
- Satisfaction Rating (1–5)  
- Fiscal Year and Day of Week  
- Duration Buckets and Rounded Ratings  
- Customer demographics (Gender, Age, City)

All data is stored within a **single Excel workbook**, which also contains PivotTables and the dashboard.

---

## 🧮 KPIs & Metrics Tracked

The dashboard dynamically displays the following KPIs:
- Total Calls Handled  
- Total Purchase Amount  
- Total Call Duration  
- Average Customer Rating  
- Number of Happy Callers  
- Agent Call Rank (1–5)  
- Agent Amount Rank (1–5)

These KPIs update instantly when an agent is selected.

---

## 🧠 Pivot Analysis

Multiple PivotTables were created to support the dashboard, including:
- Calls and purchase amount by agent
- Monthly call trends
- Day-of-week call distribution
- Customer satisfaction rating distribution
- City-wise and gender-wise caller analysis
- Customer-level purchase summaries by agent

These PivotTables serve as the analytical backbone of the dashboard.

---

## 📈 Interactive Dashboard Features

- **Agent slicer (R01–R05):** Selecting an agent dynamically updates all KPIs, charts, tables, and visuals  
- **Agent ranking:** Agents are ranked from 1 to 5 based on performance metrics  
- **Call trend chart:** Monthly call volume trend visualization  
- **Day-of-week analysis:** Identifies peak operational days  
- **Gender vs city comparison:** Visual comparison of male vs female callers across cities  
- **Rating distribution:** Histogram showing customer satisfaction spread  
- **Detailed table:** Customer-level purchase amounts by agent and city with conditional formatting  
- **Dynamic visuals:** Agent image and contribution percentages update with slicer selection  

---

## 🔍 Key Insights

- Call volume and purchase contribution vary significantly across agents  
- A small subset of agents consistently ranks higher in both call handling and revenue generation  
- Certain months and weekdays experience higher call volumes, indicating staffing optimization opportunities  
- Customer satisfaction is concentrated in higher ratings (3–5), with scope for improving low-rated interactions  
- City and gender-based analysis highlights regional and demographic behavior differences  

---

## 💼 Business Impact

This dashboard enables:
- Faster performance reviews without manual reporting  
- Data-backed agent ranking and incentive planning  
- Improved staffing decisions based on call trends  
- Identification of coaching and training needs  
- Clear communication of operational performance to stakeholders  

---

## 🔄 How to Use

1. Open the Excel dashboard file from the repository  
2. Enable content if prompted  
3. Use the **Representative slicer** to select an agent  
4. Observe how KPIs, charts, rankings, and tables update dynamically  
5. Switch agents to compare performance instantly  

---

## 🧾 Notes

- All visuals are powered by PivotTables for efficient aggregation  
- Agent images are linked dynamically for enhanced dashboard clarity  
- The workbook is designed for business users with no technical background  

---

## 📌 Future Enhancements

- Add time-based slicers (month / year)  
- Introduce performance scoring weights  
- Automate data refresh using Power Query  
- Export executive summary reports in PDF format  

---

## 👤 Author

**Masthan Shaik**  
IIT Patna  
GitHub: https://github.com/MasthanShaik-2301
