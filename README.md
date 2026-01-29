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
### **Page 1: Risk & Financial Exposure**

Purpose:
To provide an executive-level overview of governance risk concentration and potential financial exposure across the enterprise.

🔍 Key Visuals

KPI Cards

Records Assessed

Average Compliance Risk

Estimated Financial Exposure (€)

Percentage of High-Risk Records

ZoomCharts Drill Down (Hero Visual)

Drill path: Business Domain → Table Name → Field Name

Measures: Average Compliance Risk, Total Estimated Fine (€)

Compliance Risk by Business Domain

Highlights domains with the highest aggregated risk

Insight Panel

Summarizes key governance risk drivers in plain language

### **🧭 Filters: Business Domain, GDPR Relevant, Compliance Status**

### **Page 2: Trust & Governance Maturity**

Purpose:
To assess data trustworthiness, governance maturity gaps, and their alignment with business impact.

🔍 Key Visuals

ZoomCharts Drill Down

Drill path: Data Classification → Critical Data Element → Audit Rating

Measures: Average Governance Maturity, Average Data Quality

Business Impact vs Governance Maturity (Scatter Plot)

Identifies high-impact data with weak governance controls

Insight Panel

Highlights GDPR-relevant and critical data elements requiring priority attention

### **🧭 Filters: Business Domain, GDPR Relevant, Compliance Status***

## **⚙️ Key Features**

Interactive ZoomCharts Drill Down visuals for multi-level exploration

Clear separation of Risk & Exposure vs Trust & Maturity

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
<img width="1164" height="738" alt="fp20-challenge-34Page1" src="https://github.com/user-attachments/assets/b0a4eaf9-5e0a-44c8-ae85-859e518db0ed" />


### **Page 2 – Trust & Governance Maturity**
<img width="1160" height="741" alt="fp20-challenge-34Page2" src="https://github.com/user-attachments/assets/94d2f8c5-6cb8-4bbb-9c39-b524de114432" />


### **Data Model (Optional)**
<img width="1089" height="708" alt="Screenshot 2026-01-29 200910" src="https://github.com/user-attachments/assets/d90ffe32-d6ff-472e-9295-37b99fccb8a3" />


## **🙌 Acknowledgements**

Thanks to FP20 Analytics and ZoomCharts for providing the dataset, tools, and opportunity to explore enterprise data governance through practical analytics.
