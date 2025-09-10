# Shala-Students-Regional-Campaign-Analysis
Analyzed Shala's student campaign performance across regions to measure reach, CTR, CPC, and CPR. Visualized age-wise engagement trends and regional impact using Power BI to provide actionable insights for optimizing future campaigns.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Dataset Overview](#dataset-overview)
- [Data Cleaning Process](#data-cleaning-process)
- [Insights & Findings](#insights--findings)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)

---
## Project Overview

This Power BI Project analyzes Shala's digital marketing campaign performance across various age groups and campaign IDs. Key metrics include Cost Per Click (CPC), Cost Per Result (CPR), Click-Through Rate (CTR), and audience reach, and this dashboard provides a visual analysis of campaign reach segmented by age groups and campaign IDs. It helps marketers understand which campaigns are most effective at reaching specific age demographics, enabling data-driven decisions for future campaign targeting.

---
## Tools Used

- *Microsoft Excel* – For data cleaning and transformation  
- *Microsoft Excel* – For further cleaning, pivot tables, KPIs, and visualizations  
- *GitHub* – For documentation and version control

---

## Dataset Overview

Of course. Here is a comprehensive overview of the dataset, structured for your GitHub documentation.

---

### **Dataset Overview: Marketing Campaign Performance**

This dataset contains detailed performance metrics for **11 distinct marketing campaigns** run by the team, targeting **Educators/Principals** and **Students** across various international geographies and age groups.

#### **1. Key Details**
*   **Source:** `Copy of Marketing Team Data.xlsx`
*   **Sheet:** `Sheet1`
*   **Records:** 41 rows (each representing a unique campaign, age group, and geography combination)
*   **Columns:** 17 key performance indicators (KPIs)

#### **2. Campaign Summary**
The campaigns fall into two main audience categories:
1.  **Educators and Principals:** Targeted by a single, broad campaign (`Campaign 1: SHU_6`) across multiple age groups in "Group 1" countries.
2.  **Students:** Targeted by 10 specific campaigns (`Campaign 2` to `Campaign 11`), each focused on a specific country or region (e.g., India, Nigeria, UK, USA).

#### **3. Dimensions (Segmentation)**
The data is segmented along three primary dimensions, allowing for granular analysis:
*   **Campaign:** ID and Name (e.g., `Campaign 6: SHU_Students (India)`)
*   **Audience:** `Educators and Principals` or `Students`
*   **Demographics:**
    *   **Age:** `13-17`, `18-24`, `25-34`, `35-44`, `45-54`, `55-64`
    *   **Geography:** Specific countries (e.g., Australia, Nigeria) or grouped regions.

#### **4. Metrics (KPIs)**
The dataset includes a full funnel of marketing performance indicators:

 Metric | Description |
| :--- | :--- |
| **Reach** | Number of unique users who saw the ad. |
| **Impressions** | Total number of times the ad was displayed. |
| **Frequency** | Average number of times each user saw the ad (Impressions / Reach). |
| **Clicks** | Total number of clicks on the ad. |
| **Unique Clicks** | Number of unique users who clicked. |
| **Unique Link Clicks (ULC)** | Clicks specifically on the link in the ad. |
| **CTR (%)** | Click-Through Rate (Clicks / Impressions). |
| **Unique CTR (%)** | Unique Click-Through Rate (Unique Clicks / Reach). |
| **Amount Spent (INR)** | Total cost of the campaign segment in Indian Rupees. |
| **CPC (INR)** | Cost Per Click (Amount Spent / Clicks). |
| **CPR (INR)** | Cost per Result (likely Cost per Unique Link Click: Amount Spent / ULC). |

#### **5. Potential Use Cases for Analysis**
This dataset can be used to answer critical business questions, such as:
*   **Audience Analysis:** Which age group within a country is most cost-effective to target?
*   **Campaign Performance:** Which campaign delivered the lowest Cost per Result (CPR) or highest CTR?
*   **Geographic Analysis:** Which country or region provides the highest engagement rates for students?
*   **Budget Optimization:** How should the marketing budget be allocated across campaigns and demographics to maximize reach or conversions (ULC) while minimizing cost?
*   **Creative & Frequency Analysis:** Is there a correlation between higher frequency and higher engagement (CTR), or does it lead to ad fatigue?

#### **6. Data Source & Notes**
*   The currency for all financial metrics (Spend, CPC, CPR) is **Indian Rupees (INR)**.
*   The "Result" in **Cost per Result (CPR)** is inferred to be a **Unique Link Click (ULC)**, as it is the primary conversion action for lead generation.
*   This clean, structured dataset is ready for analysis, visualization in dashboards, and deriving strategic insights for future marketing planning.


---
## Data Cleaning Process

Of course. Here is a short note on the data cleaning process suitable for your GitHub documentation.

***

### **Data Cleaning Process**

Before visualization, the raw campaign data underwent a structured cleaning and preparation process to ensure accuracy and consistency in the dashboard.

**1. Data Acquisition & Assessment:**
*   Collected raw data from source systems (e.g., Facebook Ads Manager, Google Analytics, CRM exports).
*   Performed an initial assessment to identify major issues like missing values, inconsistencies, and outliers.

**2. Handling Missing & Inconsistent Values:**
*   **Missing `Age` or `Campaign ID`:** Records with critical missing segmentation fields (Age Group, Campaign ID) were excluded from the analysis to maintain metric integrity.
*   **Inconsistent Age Groupings:** Standardized age ranges to predefined segments (13-17, 18-24, 25-34). Raw ages were mapped to these groups for a unified analysis.
*   **Inconsistent Campaign Naming:** Validated and aligned Campaign IDs and names to ensure each unique campaign was represented correctly (e.g., merging "Campaign_03" and "Campaign 3").

**3. Data Transformation & Validation:**
*   **Metric Calculation:** The `Reach` metric was summed (`Sum of Reach`) for each unique combination of Campaign ID and Age Group.
*   **Percentage Calculation:** Percentages shown in the tooltips were calculated as `(Campaign Reach within Age Group / Total Reach for that Age Group) * 100`.
*   **Data Type Validation:** Ensured `Reach` was stored as an integer and `Campaign ID` as a categorical string.

**4. Output:**
The result was a clean, aggregated dataset structured for optimal use in the dashboard's visualizations, ensuring that the insights presented are reliable and accurate.

---
## Insights & Findings

- Campaign 10 shows the highest CPC and CPR, with significant reach in the 13–17 age group.
- CTR trends are visualized alongside costs, helping identify performance-efficiency relationships.
- The bubble chart compares CTR with reach, segmented by age, providing visual clarity on engagement levels across demographics.

---
## Dashboard

![Students Regional Campaign dashboard] (<img width="1193" height="698" alt="Shala Dashboard (Age Campaign)" src="https://github.com/user-attachments/assets/ad03ad0c-cd65-45a7-9cfb-41f3909f970c" />)
(<img width="1196" height="699" alt="Shala Dashboard i" src="https://github.com/user-attachments/assets/af895cea-bfbb-4423-9e6e-3f052426a786" />)

---
## Conclusion

To uncover actionable insights, optimize ad spend, and target high-performing age groups.



