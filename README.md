# Healthcare-Performance-Dashboard
Interactive Power BI dashboard analyzing 2018-21 healthcare patient wait-lists by case type, age, time band &amp; specialty.

### *Objective:*

To analyze and visualize average patient wait times across different case types, specialties, age groups, and time bands to help healthcare providers reduce wait times, prioritize critical specialties, and optimize patient care delivery.

---

### *Questions (KPIs):*
1. What is the current total patient wait list count and how has it changed compared to the previous year?
2. What is the distribution of patient cases among Outpatient, Inpatient, and Day Case categories?
3. How are patients segmented by time bands and age groups?
4. Which specialty groups have the highest wait list volumes?
5. What are the trends over time in patient wait lists for Inpatient, Day Case, and Outpatient?
6. Which age groups are waiting the longest in each time band?

---

### *Key Performance Indicators (KPIs):*
* Latest Month Wait List Count
* Previous Year Same Month Wait List Count
* Case Type Distribution (Outpatient, Inpatient, Day Case)
* Monthly Trend for Wait List by Case Type
* Wait List Segmentation by Time Band & Age Profile
* Specialty-wise Wait List Count
* Age vs Time Band Wait List Breakdown

---

### *Process Followed:*

1. *Data Collection:*

   * Used three datasets: [Inpatient](Datasets/Inpatient), [Outpatient](), and [Mapping_Specialty]().

2. *Data Cleaning & Transformation:*

   * Cleaned raw datasets in Power Query (handled nulls, renamed columns, unified formats).
   * Merged specialty mappings for enriched analysis.

3. *Data Modeling in Power BI:*

   * Established relationships across case types, specialties, age groups, and time bands.
   * Created DAX measures for KPI metrics, trends, and tooltips.

4. *Data Visualization:*

   * Designed three interactive dashboards:
     * **Summary Dashboard**
     * **Detailed View Dashboard**
     * **Specialty Breakdown Tooltip Dashboard**

   * Implemented dynamic filters (slicers) and tooltips for interactivity.

---

### *Project Insights:*

* *Highest Case Type:* Outpatient cases dominate the total wait list volume.
* *Longest Waits:* Age group 16–64 is most impacted in 18+ month time bands.
* *Top Specialties by Volume:* Bones, General, and ENT have the highest number of waitlisted patients.
* *Time Band Insight:* Majority of patients fall under the 0–3 month band, but critical delays seen in 18+ months band.
* *Trend Observation:* Steady increase in wait list volumes observed from 2019 to 2021 across all case types.

---

### *Final Conclusion:*

This Power BI project enabled a data-driven analysis of the healthcare system’s patient wait list. The insights empower healthcare administrators to understand trends, identify bottlenecks in specialties, and focus on reducing wait times for vulnerable age groups. With interactive visualizations, decision-makers can better allocate resources and optimize care delivery strategies for improved patient outcomes.

---
