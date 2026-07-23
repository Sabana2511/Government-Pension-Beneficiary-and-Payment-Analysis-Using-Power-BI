# 📊 Government Pension Beneficiary & Payment Analysis Using Power BI

## 📌 Project Overview

This project analyzes government pension beneficiary and payment data using Microsoft Power BI. 
The dashboard provides interactive insights into beneficiary distribution across states, districts, 
residence types, and pension schemes. It also analyzes pension payment disbursement through Bank, 
Post Office, Money Order, and Cash to identify regional patterns and support 
data-driven decision-making.

---

## 🎯 Project Objectives

- Analyze pension beneficiaries across different pension schemes.
- Compare beneficiary distribution between Rural and Urban areas.
- Evaluate State-wise and District-wise beneficiary coverage.
- Analyze pension payment disbursement through different payment channels.
- Identify major pension schemes based on beneficiary records.
- Monitor pension disbursement and beneficiaries without payment.
- Generate meaningful insights to support pension program monitoring and planning.

---

## 🌐 Data Source

The dataset was obtained from the **National Data and Analytics Platform (NDAP), NITI Aayog**.

**Domain:** Government Welfare / Public Administration / Social Security

**Source:**  
https://ndap.niti.gov.in/dataset/6710?filter_id=5546

---

## 📂 Dataset Attributes

| Attribute | Description |
|---|---|
| Country | Country where the pension scheme is implemented |
| State | State where beneficiaries are located |
| District | District within the respective state |
| Year | Financial year of the pension data |
| Residence Type | Classification of beneficiaries as Rural or Urban |
| Scheme Code | Code representing the pension scheme |
| Total Number of Beneficiaries | Total beneficiaries enrolled under the specified scheme |
| Pension Payment Through Bank | Number of payments made through banks |
| Pension Payment Through Post Office | Number of payments made through post offices |
| Pension Payment Through Money Order | Number of payments made through the money order system |
| Pension Payment Through Cash | Number of payments made through cash |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Calculated columns, measures, and KPIs
- **Data Modeling** – Structuring and optimizing the data model

---

## 🧹 Data Preprocessing

The raw dataset was imported into Power BI and cleaned using Power Query to ensure data consistency 
and accuracy. Data types were corrected for all columns, and the financial year was extracted into a 
separate Year column for analysis. Column names were standardized for better readability. 
New calculations such as **Pension Disbursed** and **Beneficiaries Without Payment** were created to 
support payment analysis. The transformed dataset was then loaded into the Power BI data model.

---

## 🧩 Data Modeling & DAX

The dataset was organized into a Power BI data model to support analysis across **State, District, 
Year, Residence Type, and Scheme Code**.

<img width="897" height="622" alt="image" src="https://github.com/user-attachments/assets/7945981b-bf9b-4b36-ae2c-1cb038547103" />


DAX calculations were created for key metrics such as:

- Total Beneficiaries
- Pension Disbursed
- Beneficiaries Without Payment
- Payment Distribution

These calculations were used to create dynamic KPI cards and interactive visualizations for 
effective analysis and reporting.

---

## 📊 Dashboard & Visualizations

## 📸 Dashboard Preview

<img width="1337" height="751" alt="image" src="https://github.com/user-attachments/assets/5e49393a-80b7-4515-9a8e-f1dfd0e88742" />


The Power BI dashboard includes:

- 📌 KPI Cards
- 📊 Beneficiary Analysis by Pension Scheme
- 🗺️ State and District-wise Analysis
- 🏡 Rural vs Urban Comparison
- 💳 Payment Method Analysis
- 📈 Trend Analysis
- 🥧 Payment Distribution
- 🎛️ Interactive Slicers
- 🔍 Drill-down Analysis

Users can interactively filter the dashboard by:

- Year
- State
- District
- Residence Type
- Scheme Code

---

# 📈 Data Analysis & Key Insights

## 📊 1. Descriptive Analysis — What Happened?

The dashboard provides an overall view of **43M total beneficiaries** across **30 States, 
625 Districts, and 33 Pension Schemes**.

- **43M** total beneficiaries
- **22M** pension disbursements
- **21M** beneficiaries shown as without payment in the dashboard KPI
- **39M (90.18%)** beneficiaries are from Rural areas
- **4M (9.82%)** beneficiaries are from Urban areas
- **14M** payments through Bank
- **6M** payments through Cash
- **2M** payments through Post Office
- **62K** payments through Money Order

Among the schemes, **IGNOAPS (1,175)** has the highest number of beneficiary records, 
followed by **IGNWPS (1,079)** and **IGNDPS (1,069)**.

---

## 🔍 2. Diagnostic Analysis — Why Did These Patterns Occur?

The analysis indicates a strong rural focus in pension coverage, with **90.18%** of beneficiaries
residing in rural areas.

Payment methods vary significantly across states. **Odisha** shows approximately **4.0M Cash payments** 
compared with **1.1M Bank payments**, indicating a strong reliance on cash-based pension delivery.

In comparison, **West Bengal** records approximately **2.3M Bank payments** and **0.2M Post Office payments**, 
highlighting differences in payment patterns between states.

At the scheme level, **IGNOAPS** records approximately:

- **7.8M Bank payments**
- **2.5M Cash payments**
- **1.4M Post Office payments**

This indicates that payment channel preferences and delivery mechanisms vary across both states and 
pension schemes.

---

## 🔮 3. Predictive Analysis — What May Happen?

Based on the observed patterns, future pension delivery demand is likely to remain strongly concentrated in
rural areas due to the **90.18% rural beneficiary share**.

Bank-based payments may continue to grow as banking and digital payment infrastructure becomes more accessible.

States with high cash dependency, such as Odisha, may potentially experience a shift toward bank-based payment 
channels if financial access and beneficiary adoption improve.

Future analysis should track:

- Year-wise beneficiary growth
- Year-wise pension disbursement
- Changes in beneficiaries without payment
- Movement from Cash to Bank payments
- Rural vs Urban beneficiary trends

---

## 🎯 4. Prescriptive Analysis — What Should Be Done?

### 1. Strengthen Rural Pension Delivery

With **39M rural beneficiaries (90.18%)**, priority should be given to improving rural banking infrastructure, 
local service centers, and payment accessibility.

### 2. Monitor Beneficiaries Without Payment

The **21M Beneficiaries Without Payment KPI** should be regularly monitored at State, District, and Scheme 
levels to identify potential payment gaps.

### 3. Improve Payment Channel Accessibility

Although Bank is the leading payment channel with **14M payments**, approximately **6M payments** are made 
through Cash. Payment strategies should consider local infrastructure and beneficiary accessibility.

### 4. Investigate High-Cash States

Odisha's approximately **4.0M Cash payments** compared with **1.1M Bank payments** indicate an opportunity for 
deeper analysis of banking access, beneficiary preferences, and payment infrastructure.

### 5. Focus on Major Pension Schemes

The leading schemes — **IGNOAPS (1,175), IGNWPS (1,079), and IGNDPS (1,069)** — should be closely monitored 
because improvements in their delivery can have a significant impact on overall pension coverage.

### 6. Track Trends Over Time

Future dashboard updates should monitor changes in beneficiaries, pension disbursement, beneficiaries without payment, 
and payment methods to evaluate pension program performance.

---

# ⭐ Overall Key Insights

- The dashboard analyzes **43M beneficiaries** across **30 States, 625 Districts, and 33 Pension Schemes**.
- Pension coverage is highly concentrated in rural areas, with **90.18%** of beneficiaries from Rural areas.
- **Bank payments (14M)** are the leading payment channel, followed by **Cash (6M)**, **Post Office (2M)**,
  and **Money Order (62K)**.
- The dashboard records **22M pension disbursements** and shows **21M beneficiaries without payment** based on
  the defined dashboard KPI.
- Payment patterns vary significantly across states, with Odisha showing approximately **4.0M Cash payments**
  compared with **1.1M Bank payments**.
- The major schemes **IGNOAPS, IGNWPS, and IGNDPS** have the highest beneficiary record counts.

---

# 🎯 Overall Recommendations

1. **Strengthen Rural Pension Services** by improving banking infrastructure and payment accessibility
   for the **39M rural beneficiaries**.
2. **Monitor the 21M Beneficiaries Without Payment KPI** at State, District, and Scheme levels
   to identify payment gaps.
3. **Optimize Payment Channels** by expanding efficient bank-based payment options while maintaining
   accessible alternatives.
4. **Investigate High Cash Dependency** in states such as Odisha to understand infrastructure and
   accessibility challenges.
5. **Prioritize Major Pension Schemes** such as IGNOAPS, IGNWPS, and IGNDPS for continuous performance monitoring.
6. **Track Year-wise Trends** in beneficiaries, pension disbursement, beneficiaries without payment, and payment methods.

---

## 💼 Skills Demonstrated

**Data Cleaning | Power Query | Data Modeling | DAX | KPI Development | Data Visualization | Power BI Dashboard Development | Data Analytics | Business Intelligence**

---

## 💡 Conclusion

This project demonstrates how Power BI can transform government pension data into meaningful 
and actionable insights.

The analysis highlights a predominantly rural beneficiary base, significant variation in payment methods 
across states and schemes, and a substantial number of beneficiaries without payment based on the dashboard KPI.

Strengthening rural payment infrastructure, improving access to efficient payment channels, and continuously 
monitoring payment gaps can help improve the effectiveness and reach of pension delivery.

---

## 🏷️ Tags

`#PowerBI` `#DataAnalytics` `#DataAnalysis` `#DataVisualization` `#BusinessIntelligence` `#PowerQuery` 
`#DAX` `#DataModeling` `#GovernmentData` `#PensionAnalytics` `#Dashboard` `#DataAnalyst` `#PortfolioProject`

---

## 👤 Author

### Sabana Asmi

Aspiring Data Analyst

---

## 👤 Project Type

**Data Analytics | Business Intelligence | Power BI Portfolio Project**
