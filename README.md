# IT Service Desk Analytics – Power BI Project

## 📊 Project Overview
This project is an end-to-end **IT Service Desk Analytics Dashboard** built using **Power BI**.  
It provides insights into ticket volume, incident trends, SLA compliance, and service performance.

The dashboard helps IT managers and stakeholders monitor operational efficiency and improve service quality.

---

## 🎯 Business Objectives
- Analyze IT service desk ticket volume and trends
- Identify high-impact categories and priorities
- Measure SLA compliance and resolution performance
- Support data-driven decision-making

---

## 🛠 Tools & Technologies
- Power BI
- Power Query
- DAX
- Star Schema Data Modeling

---

## 🔄 Data Preparation
- Cleaned and transformed raw data using Power Query
- Handled missing values and standardized date/time formats
- Converted handle time from minutes to hours
- Removed duplicates and irrelevant fields

---

## 🧩 Data Model
- Implemented a **Star Schema**
- Fact Table: `Fact_Incidents`
- Dimension Tables:
  - `Dim_Date`
  - `Dim_TicketCategory`
  - `Dim_ConfigurationItem`
  - `Dim_KnowledgeBase`

---

## 📐 DAX Measures
- Total Tickets
- Closed Tickets
- Reopened Tickets
- Average Handle Time
- Average Resolution Time
- SLA Compliance %
- SLA Breached Tickets

---

## 📄 Dashboard Pages

### 1️⃣ Executive Overview
- Total Tickets
- Closed Tickets
- Reopened Tickets
- Average Handle Time
- Monthly Incident Trend
- Ticket Distribution by Priority

![Executive Overview](Images/Page1_Executive_Overview.png)

---

### 2️⃣ Incident & Category Analysis
- Ticket Volume by Category
- Incident Contribution by Configuration Item
- Category & Priority Analysis
- Monthly Trend by Top Categories

![Incident Analysis](Images/Page2_Incident_Category.png)

---

### 3️⃣ SLA & Performance Analysis
- SLA Compliance %
- SLA Breached Tickets
- Average Resolution Time
- Priority Ranking Trend
- Ticket Breakdown Analysis

![SLA Analysis](Images/Page3_SLA_Performance.png)

---

## 🚀 Key Learnings
- Real-world ITSM analytics experience
- End-to-end Power BI workflow
- Strong data modeling and DAX skills
- Business-focused dashboard design

---

## 📌 Future Enhancements
- Agent-level performance analysis
- SLA target vs actual comparison
- Drill-through and tooltip pages

---


