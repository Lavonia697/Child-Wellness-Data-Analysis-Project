# Child-Wellness-Data-Analysis-Project

**By:** Lavonia Munedzimwe

**Role Focus:** Data Entry Specialist | Junior Data Analyst

**Contact:**
lavoniamandi@icloud.com | 🔗 https://www.linkedin.com/in/lavonia-munedzimwe-a89221294/

This project analyzes child wellbeing, attendance patterns, and health checkup trends using Excel-based data cleaning, transformation, pivot analysis, and visualization. The goal is to uncover insights that can support decision-making in child wellness programs.

---

## Motivation
This project was motivated by the need for accessible data insights in child health and school wellbeing programs - especially in resource limited environments.

---

## Table of Contents
- Project Overview
- Dataset Structure
- Data Processing Workflow
- Repository Structure
- Insights
- Summary of Findings
- Recommendations
- How to Nagivate This Repository
- Data Dictionary
- Tools Used
- Author

## Project Overview
This project analyzes child health and wellbeing data across multiple countries to uncover relationships between attendance, health checkup completion, and wellbeing scores. The goal is to assist NGOs and community programs in designing initiatives that improve school engagement and student wellbeing.

---

## Project Objectives
- Understand key factors related to child wellbeing.
- Analyze attendance patterns and how they relate to wellbeing.
- Explore age-based health engagement through checkup-up frequently.
- Communicate findings using dashboards, pivot charts and reports.

  ---

## Dataset Description

- **Raw Data** – initial unmodified dataset  
- **Cleaned Data** – standardized formatting & missing values reviewed  
- **Modified Data** – new fields created (age groups, attendance category, checkup status)  
- **Analysis File** – pivot tables & dashboards supporting insights

---

## Data Processing Workflow
**1. Raw Data** - imported from Excel

**2. Cleaning**
- Removed duplicates
- Standardized capitalization and formatting
- Handled missing values (median for wellbeing)
- Date formatting standardized (International format: YYYY-MM-DD)
  
**3. Feature Engineering (Modified Data)**
  - `Age_Group` column created (5-10, 11-15, 16-18)
  - `Attendance_Category` (Low <70%, Medium 70-89%, High ≥90%)
  - `Checkup_Status` (Checkup Completed / Not Completed)
 
    ---


## Repository Structure
data/                - Raw, cleaned, and modified datasets

analysis/            - Excel workbook with pivots, charts & dashboard

outputs/visuals/     - Final graphs exported as PNG

README.md            - Project summary & insights

---

## Insights
+ Children with higher attendance often show slightly higher wellbeing, suggesting school engagement supports mental and social wellness.
+ 55% have not completed a recent health checkup, highlighting a potential gap in preventive care access.
+ Wellbeing varies across countries, indicating environmental and support differences.
+ Age and gender groups shows similar wellbeing distribution, minor variations but no strong bias.
+ Health checkups show mild association with wellbeing, suggesting further investigation is valuable.

  ---

## Summary of Findings
+ Good attendance strongly aligns with better wellbeing.
+ Younger children engage more frequently in medical checkups.
+ Gender does not significantly impact wellbeing.
+ Regional variation suggests resource/access awareness differences.
 
    ---

## Recommendations
 1. **Increase health outreach programs for older children**
  
2. **Introduce attendance wellbeing monitoring for early intervention**
  
3. **Support community health access in low-compliance regions**
  
4. **Develop wellness workshops to improve mental health awareness**
 
5. **Partnerships with schools for regular checkup drives**
 
  ---

## Next Steps
- Explore machine-readable data formats to automate updates
- Intergrate additional demographic variables
- Build interactive dashboards using Power BI or Tableau

  ---

## How to Navigate This Repository

1. Open the `Data/` folder to review raw, cleaned and modified datasets.
2. Review the Excel workbook in `Analysis-Ready/` to see pivot tables and dashboards.
3. Open the `Visualizations/` folder for exported charts.
4. Read the final report and presentation in `Report/`.
5. Use the PDF or PPTX for presenting or reviewing insights offline.

---

## Data Dictionary
| Column              | Description                 | Type        | Example    |
| ------------------- | --------------------------- | ----------- | ---------- |
| Child_ID            | Unique identifier           | Integer     | 145        |
| Age                 | Age of child                | Integer     | 12         |
| Gender              | Male/Female                 | Categorical | Female     |
| Country             | Country of residence        | String      | Kenya      |
| Attendance_Rate     | School attendance %         | Numeric (%) | 87%        |
| Wellbeing_Score     | Self-reported score 1-10    | Numeric     | 7          |
| Last_Checkup_Date   | Most recent medical checkup | Date        | 12/05/2024 |
| Checkup_Status      | Derived field               | Categorical | Completed |
| Age_Group           | Derived age buckets         | Categorical | 11-15      |
| Attendance_Category | Derived attendance grouping | Categorical | Medium     |

---
 
## Tools Used

1. **Microsoft Excel**
    - Data cleaning and transformation
   -  Pivot tables and charts
     - Dashboard creation
2. **PDF & PowerPoint**
   - Reporting and presentation
3. **GitHub** 
      - Deployment and documentation

---
    
## Author
Lavonia Munedzimwe - Data Entry Specialist | Junior Data Analyst
lavoniamandi@icloud.com | 🔗 https://www.linkedin.com/in/lavonia-munedzimwe-a89221294/


