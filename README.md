# 📊 Loan Risk Analytics Dashboard (Power BI)

## 📌 Project Overview
This project focuses on analyzing loan applicant data to identify **default risk patterns**, **high-risk client profiles**, and **key demographic & financial insights**.  
The solution was built end-to-end in **Power BI**, covering data cleaning, modeling, DAX measures, and visualization.

---

## ⚙️ Features
- **Data Cleaning & Preprocessing**
  - Removed high-missing columns (>60%)
  - Replaced missing values with median, zero, or "Unknown"
  - Grouped categorical features (Income, Employment, Organization Type, etc.)
  - Converted date-based columns (Age, Employment, Registration) into meaningful groups  

- **Data Modeling**
  - Set correct data types (Whole Number, Decimal, Text)
  - Built derived columns (Age Group, Income Group, Risk Score Group)
  - Created custom **DAX measures** for KPIs  

- **Dashboard Design**
  - **Page 1: Customer Risk Profile** – Demographics vs Default Rate  
  - **Page 2: Loan Risk Segmentation** – Income, Employment, Risk Score Patterns  
  - **Page 3: High Risk Patterns** – EXT source scores, address stability, org type analysis  
  - Dark theme (Black & Orange) with slicers and page navigation  

---

## 📊 Key Metrics (DAX Measures)
- Total Applications  
- Total Loan Amount  
- Average Loan & Income  
- Default Rate (%)  
- High Risk Clients %  
- Risk Category & Risk Score  

---

## 🛠️ Tools & Technologies
- Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- Dataset: `application_data.csv`  

---

## 📂 Deliverables
- `Final_Project.pbix` → Power BI dashboard  
- `Cleaned_application_data.csv` → Processed dataset  

---

## 🚀 Conclusion
This project demonstrates the **end-to-end data analytics workflow**:  
from **raw data → cleaning → modeling → DAX → visualization**, resulting in a professional, interactive dashboard for loan risk analysis.  

---
