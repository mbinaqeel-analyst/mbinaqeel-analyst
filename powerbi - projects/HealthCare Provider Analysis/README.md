## 📌 Project Overview
This project involves the development of a comprehensive 4-page Business Intelligence solution designed to optimize hospital operations and financial transparency. By integrating 8 disparate datasets containing over 5,000 patient records, this dashboard provides a 360-degree view of facility performance, provider efficiency, and patient demographics.

---

## 🚀 Key Features & Dashboards

### 1. Financial Overview 💰
* **Revenue Tracking:** Aggregated $3.36M in total revenue across Treatment, Medication, and Room costs.
* **Departmental Performance:** Identified **Cardiology** and **Orthopedics** as the primary financial drivers.
* **Cost Analysis:** Breakdown of revenue by Insurance Provider (Aviva, AXA, Allianz).

### 2. Provider Insights 👨‍⚕️
* **Efficiency Matrix:** A scatter chart analysis correlating patient volume with revenue per visit.
* **Satisfaction Benchmarking:** Tracked individual doctor performance against a facility average of 3.8/10.
* **Dynamic Directory:** Integrated provider images and metadata for a modern, interactive UX.

### 3. Trend Analysis 📈
* **Seasonality Mapping:** Identified a significant **300% volume surge** in January 2025.
* **Service Evolution:** Analyzed the shift between Inpatient, Outpatient, and Emergency services over a 24-month period.

### 4. Demographics & Patient Mix 👥
* **Clinical Focus:** Pinpointed **Hypertension** as the #1 diagnosis by volume.
* **Referral Funnel:** Visualized patient acquisition channels, highlighting a high percentage of self-referrals.

---

## 🛠️ Technical Implementation

### Data Architecture (Star Schema)
The project utilizes a robust Star Schema to ensure high-performance filtering and scalability.
* **Fact Table:** `Visits`
* **Dimension Tables:** `Patients`, `Providers`, `Departments`, `Diagnoses`, `Procedures`, `Insurance`, `Cities`, and a custom `Date` table.



### Advanced DAX & ETL
* **Power Query (M):** Cleaned and transformed raw CSVs, including complex logic for `Length of Stay` and `Total Room Cost` calculations.
* **Time Intelligence:** Authored DAX measures for Month-over-Month (MoM) growth and Previous Month (PM) comparisons.
* **Sync Slicers:** Implemented report-wide interactivity, allowing a single filter to update all 4 analytical pages simultaneously.

---

## 📊 Business Insights & Recommendations
1. **Operational Planning:** The January volume spike suggests the need for seasonal staffing increases starting in late Q4.
2. **Patient Experience:** With an average satisfaction of 3.8, there is a strategic opportunity to implement post-discharge follow-up programs.
3. **Revenue Capture:** Standardizing billing for "High-Efficiency" departments could recapture leaked revenue in underperforming sectors.
