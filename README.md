# 📊 Healthcare Analytics Dashboard: Catheterization & Educational Hospitals Management
> **إدارة المستشفيات و المعاهد التعليمية - لوحة متابعة عمليات القسطرة**

An interactive operational & clinical analytics dashboard designed for managing educational hospitals and healthcare institutes. This dashboard provides key insights into catheterization procedures (Peripheral, Cerebral, and Cardiac), equipment usage, operational trends, and key performance metrics across various hospital units.

---

## 📌 Dashboard Overview

The dashboard focuses on monitoring hospital capacity, monthly procedure volumes, percentage changes, and equipment availability to optimize decision-making and resource allocation.

### 🖼️ Screenshot
<img width="3251" height="1829" alt="image" src="https://github.com/user-attachments/assets/941aeabd-75c3-4b01-be32-02bc2761fd2d" />
<img width="3256" height="1840" alt="image" src="https://github.com/user-attachments/assets/84caa6b8-490f-493e-81c7-6416e9de4d9b" />
<img width="3291" height="1830" alt="image" src="https://github.com/user-attachments/assets/a30fd32a-e6ef-4d51-80ed-b92980b7555c" />
<img width="3669" height="1854" alt="image" src="https://github.com/user-attachments/assets/813af278-f5d0-4f23-82d8-030c4a0f4c8c" />

 <!-- Replace with your actual relative image path or hosted URL -->

---
### 🖼️ Video Walkthrough
https://youtu.be/3J8WPXKTAOQ

## ✨ Key Features & Visualizations

1. **🏥 Unit Performance Comparison (الوحدة by عدد الأجهزة الحالي and Sum of عدد حالات قسطرة طرفية)**
   - **Type:** Clustered Bar / Column Chart
   - **Metrics:** Compares total Peripheral Catheterization cases against available working equipment across major hospital units (e.g., *El-Sukkar / Al-Galaa*, *El-Sahel*, *Damanhour*, *Shebin*, *El-Matariya*, *Ahmed Maher*).

2. **⚙️ Monthly Equipment Availability (عدد أجهزة القسطرة العاملة by Month)**
   - **Type:** Line Chart
   - **Metrics:** Tracks the count of active catheterization devices operating per month (fluctuating from 20 up to 22 devices).

3. **🎯 Peripheral vs. Total Volume Gauge (إجمالي القساطر الطرفية من إجمالي القساطر)**
   - **Type:** Gauge Visual / KPI
   - **Metrics:** Measures total peripheral catheterization volume (847 cases) relative to overall hospital capacity/targets.

4. **📈 Total Cases Over Time (إجمالي الحالات على مدار الشهور)**
   - **Type:** Filled Area Line Chart with Benchmark Reference Line
   - **Metrics:** Shows monthly total patient volume with an **Average Benchmark Line (Avg: 85 cases)**. Dynamic trends show peaks (up to 112 cases in May) and drops across the year.

5. **📉 Month-over-Month Relative Change (التغير النسبي بين الشهر و الشهر السابق)**
   - **Type:** Trend Line Chart (Percentage Variance)
   - **Metrics:** Analyzes percentage growth or decline between consecutive months (e.g., peak growth in July at +0.33 vs. sharp drop in November at -1.00).

6. **📑 Dynamic Navigation & Multi-Level Slicers**
   - **Global Filters:** Filter data dynamically by **Month** (`January` – `October`) or **Quarter** (`Qtr 1` – `Qtr 4`).
   - **Categorical Tabs:** 
     - 🩺 **Peripheral Catheterization** (*القسطرة الطرفية*) — *Current View*
     - 🧠 **Cerebral Catheterization** (*القسطرة المخية*)
     - ❤️ **Cardiac Catheterization** (*القسطرة القلبية*)
     - 📑 Other Procedure Tabs: *Diagnostic Adult*, *Stent Expansion*, *Pacemaker Installation*, *Electrophysiology (EP)*, *Valve Balloon Dilation*.

7. **📝 Executive Insights & Key Notes (مقدمة / ملخص التنفيذي)**
   - Built-in summary highlighting actionable metrics such as:
     - Q3 overall performance vs. Q1 (-36% drop).
     - Significant month-over-month decline in September compared to August (-36%).
     - Average Q1 volume for *El-Sukkar Unit* (36 cases) vs. Q3 volume (28 cases).

---

## 🛠️ Built With

* **BI Tool:** Power BI / Tableau / Looker Studio *(Select appropriate tool)*
* **Data Sources:** Hospital Management Information System (HMIS) / Excel / SQL Database
* **Languages & Formulas:** DAX (Data Analysis Expressions) / SQL

---

## 💡 Key Business Insights Derived

* **Equipment Utilization:** Peak device deployment (22 active units) correlates directly with procedure capacity, highlighting critical asset reliance.
* **Volume Seasonality:** Procedure volumes peak around May (112 cases) and experience steep drops toward Q4 (November).
* **Facility Benchmark:** *El-Sukkar* and *El-Sahel* handle the highest volume of peripheral catheterizations among all managed hospitals.

---
