# Customer Churn Risk & Revenue Impact Analysis  
**Excel (Power Query + Data Model) | Power BI Dashboard**

---

## 📌 Project Overview

This project analyzes customer churn behavior to identify key drivers of attrition and quantify revenue impact.  
A rule-based risk scoring model was developed to segment customers by churn probability and prioritize retention efforts.

The analytical modeling was performed in Excel using Power Query and the Data Model. An interactive executive dashboard was built in Power BI to present insights and strategic recommendations.

---

## 🎯 Business Problem

The company is experiencing a high customer churn rate, resulting in significant revenue leakage.

The objectives of this project were to:

- Identify the primary behavioral and financial drivers of churn  
- Develop a churn risk scoring model  
- Quantify revenue loss across risk and value segments  
- Provide data-driven retention recommendations  

---

## 🛠 Tools Used

### Microsoft Excel
- Power Query (Data Cleaning & Feature Engineering)
- Data Model / Power Pivot
- Pivot Tables

### Power BI
- Data Modeling
- DAX Measures
- Interactive Dashboard Design

---

## 🔎 Methodology

### 1️⃣ Data Preparation (Excel – Power Query)
- Cleaned and validated dataset (1,000,000 customers)
- Created engineered features:
  - Age Group
  - Tenure Group
  - Recency Group
  - Payment Behavior
  - Support Flag
  - Value Segment (Mean ± 1 Standard Deviation)
- Developed a rule-based **Risk Score (0–3)** using behavioral indicators

### 2️⃣ Analytical Modeling (Excel – Data Model)
- Calculated core KPIs:
  - Total Customers
  - Churn Rate
  - Total Revenue
  - Revenue Lost
- Validated churn progression across risk levels
- Analyzed revenue concentration by risk and value segments

### 3️⃣ Dashboard Visualization (Power BI)
- Executive KPI overview
- Churn driver analysis
- Revenue prioritization matrix
- Strategic summary page

---

## 📊 Key Findings

- **Total Customers:** 1,000,000  
- **Churn Rate:** 56.72%  
- **Total Revenue:** 622.35M  
- **Revenue Lost Due to Churn:** 323.62M (52%)

### Risk Model Validation
Churn increases consistently with risk score:

- Risk 0 → 33.86%
- Risk 1 → 44.55%
- Risk 2 → 58.87%
- Risk 3 → 69.75%

Risk Score 2 represents the largest revenue leakage (159.7M lost).

### Primary Drivers
- Customers with **High Payment Delay (15+ days)** churn at 63.44%  
- “Warm” (less engaged) customers churn at 57.94%  
- Contract length shows minimal influence on churn  
- Tenure has limited protective effect  

Churn appears driven more by financial and engagement friction than contract structure.

---

## 🚀 Strategic Recommendations

1. Implement proactive payment reminder and assistance programs targeting high-delay customers  
2. Prioritize retention campaigns for **Medium-Value customers in Risk Score 2**  
3. Develop personalized intervention strategies for **High-Value customers in Risk Score 3**  
4. Launch engagement campaigns to prevent “Warm” customers from escalating into high-risk segments  
5. Improve customer support experience to reduce churn triggers  

---

## 📁 Repository Structure

```
Customer-Churn-Analysis-Excel-PowerBI/
│
├── excel/
│
│   └── Churn_Analysis_Model.xlsx
│
├── powerbi/
│   └── Churn_Dashboard.pbix
│
├── screenshots/
│   ├── Executive_Overview.png
│   ├── Drivers_Page.png
│   └── Summary_Page.png
│
└── README.md
```

---

## 📌 Project Outcome

This project demonstrates:

- End-to-end data transformation (Power Query)
- Feature engineering and segmentation
- Rule-based risk modeling
- Revenue impact analysis
- Business-driven dashboard storytelling

It reflects practical Business Intelligence workflow from data preparation to executive-level insight delivery.


