# **🏛️ Enterprise Data Governance Analytics Dashboard**

FP20 Analytics × ZoomCharts Mini Challenge 34

# **📊 Overview**

This project was developed as part of the FP20 Analytics × ZoomCharts Mini Challenge 34 (January 2026 Edition).
The dashboard focuses on Enterprise Data Governance, providing a clear, business-ready view of governance risk, financial exposure, data trust, and governance maturity across domains, tables, and fields.

Using Power BI and ZoomCharts Drill Down visuals, the dashboard enables stakeholders to quickly identify high-risk data areas, assess governance maturity, and prioritize remediation efforts.

# **🔗 Dashboard Access**

Power BI Publish to Web Link:
https://app.powerbi.com/links/EAZf9PSj21?ctid=bf93bb5e-ecf0-4e3d-be0e-79b5cc527a48&pbi_source=linkShare

The dashboard is designed to balance analytics, storytelling, and usability, making it suitable for both business leaders and data governance teams.

# **🧰 Tools and Technologies**

Power BI Desktop

ZoomCharts Custom Visuals (Drill Down PRO)

DAX (Data Analysis Expressions)

Microsoft Excel (Dataset source)

Python (EDA & data profiling)

Figma (Dashboard background, header & footer design)

# **📂 Dataset**

The dataset represents a data governance register rather than transactional data.
It includes field-level governance metadata across enterprise systems.

Key data attributes include:

Business Domain, Source System, Table Name, Field Name

Data Owner & Data Steward

Data Classification (Public, Internal, Confidential, Sensitive)

Governance Maturity Score & Data Quality Score

Compliance Risk Score & Estimated Fine (€)

GDPR relevance, audit ratings, and compliance status

The dataset was pre-structured and analyzed for governance insights rather than data cleansing.

# **📄 Dashboard Structure**
### **Page 1: Governance Insights Overview**

Purpose:
Provide an executive-level snapshot of governance risk, trust, and sensitivity across the organization.

Key Elements:

KPI Strip:

Records Assessed

Avg Compliance Risk

Avg Governance Maturity

High-Risk Records (%)

Critical Data Elements (%)

ZoomCharts Drill Down – Governance Risk & Quality Signals

Drill: Business Domain → Table → Field

Measures: Compliance Risk, Data Quality

ZoomCharts Drill Down – Trust & Governance Maturity

Drill: Data Classification → Critical Data Element → Audit Rating

Supporting Visuals:

High-Risk Records by Domain

Sensitive vs Non-Sensitive Data Distribution

Filters:

Business Domain

Data Classification

Compliance Status

### **🧭 Filters: Business Domain, GDPR Relevant, Compliance Status**

### **Page 2: Ownership & Governance Actions**

Purpose:
Translate insights into accountability and action.

Key Elements:

ZoomCharts Drill Down – Ownership Accountability Distribution

Drill: Data Owner → Business Domain → Table

Highlights ownership concentration and governance load

ZoomCharts Drill Down – Sensitive Data & Access Composition

Drill: Data Classification → GDPR Relevance → Access Level

Priority Fields Table:

Sorted to surface low maturity + high risk data elements

90-Day Governance Action Plan:

Definition standardization

Ownership and stewardship assignment

Strengthened access controls and audits

## **⚙️ Key Features**

Interactive ZoomCharts Drill Down visuals for multi-level exploration

Clear separation between insight discovery (Page 1) and action planning (Page 2)

Executive-friendly KPIs and insights

Consistent design using a custom Figma background

Cross-filtering for seamless analysis

Business-ready storytelling with minimal text

## **🚀 How to Use**

Download the .pbix file from this repository

Open it in Power BI Desktop (latest version recommended)

Interact with the ZoomCharts visuals using drill-down and filters

Explore governance risks, maturity gaps, and business impact areas

## **🏆 Challenge Details**

Organizer: FP20 Analytics

Visual Partner: ZoomCharts

Challenge: FP20 Analytics × ZoomCharts Mini Challenge 34

Theme: Enterprise Data Governance & Analytics

Timeline: January 2026

## **🖼️ Dashboard Preview**

### **Page 1 – Risk & Financial Exposure**
<img width="1166" height="655" alt="fp20-challenge-34Page1" src="https://github.com/user-attachments/assets/636c1b1d-d516-4cd5-bf66-5e4904d5214a" />



### **Page 2 – Trust & Governance Maturity**
<img width="1162" height="654" alt="fp20-challenge-34Page2" src="https://github.com/user-attachments/assets/652b1865-0643-4f8a-b468-070c2bf5c291" />



### **Data Model (Optional)**
<img width="1089" height="708" alt="Screenshot 2026-01-29 200910" src="https://github.com/user-attachments/assets/d90ffe32-d6ff-472e-9295-37b99fccb8a3" />


## **🙌 Acknowledgements**

Thanks to FP20 Analytics and ZoomCharts for providing the dataset, tools, and opportunity to explore enterprise data governance through practical analytics.

## **👤 Author**

# **Aravind Teja Bastipadu**
Designed and built using Power BI & ZoomCharts
January 2026
