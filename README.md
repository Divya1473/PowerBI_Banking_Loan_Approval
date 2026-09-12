🏦 Power BI Banking Loan Approval Dashboard

📊 Project Overview

This Power BI project analyzes a banking loan dataset to understand loan approval patterns across customer demographics, income, designation, geography, property characteristics, and financial-product ownership.

The report is designed as an interactive multi-page dashboard. Users can filter the analysis by Geography and Loan Status on the relevant report pages and use KPI measures to track the overall customer and loan-approval picture.

🎯 Objectives

Analyze approved and not-approved loan applications.

Compare loan outcomes across different age groups.

Study the relationship between applicant income, loan amount, and designation.

Analyze the geographic and property-area distribution of loan customers.

Compare maximum salary across job designations.

Examine loan-customer distribution by gender, marital status, education, and self-employment status.

Explore the relationship between loan customers and ownership of financial products such as credit cards and cars.

🛠️ Tools & Technologies

Microsoft Power BI Desktop

Power Query for data preparation/transformation

DAX for calculated measures

Interactive slicers and dashboard visualizations

🗂️ Data Model

The report uses the LoanData table.

Key fields used throughout the report include:

Loan_ID

Loan_Status

AgeLabel

Geography

Designation

ApplicantIncome

LoanAmount

Property_Area

Gender

Married

Education

Self_Employed

HasCrCard

HasCar

📌 Report Pages

1. Pie Charts by Loan Status

This page provides the high-level loan-status view.

Visuals used:

KPI card with:

M_Total_Customers

M_Loan_Approved

M_Loan_Not_Approved

M_%_Approved

Pie chart showing count of Loan_ID by AgeLabel for Loan Approved records.

Pie chart showing count of Loan_ID by AgeLabel for Not Approved records.

Geography slicer.

Purpose: Compare the age-group distribution of approved and not-approved loan customers while monitoring the overall approval KPIs.

2. LoanVsIncome Dual-Axis Chart

This page studies income and loan amount across job designations.

Visuals used:

Line and clustered-column combo chart using:

Designation

ApplicantIncome

LoanAmount

Scatter chart using the same analytical fields.

Geography slicer.

Loan_Status slicer.

KPI card with the main loan measures.

Purpose: Compare applicant income with loan amount and observe how the relationship changes across designations, geography, and loan status.

3. Geographic & Property Breakdown

This page focuses on the distribution of loan customers by property area.

Visuals used:

Pie chart using Property_Area and count of Loan_ID.

Geography slicer.

Loan_Status slicer.

KPI card with the main loan measures.

Purpose: Understand how loan customers are distributed across property areas and how the distribution changes after applying geography or loan-status filters.

4. Max Salary as per Designation

This page compares the maximum salary associated with different designations.

Visuals used:

Clustered bar chart:

Designation

M_Max_Salary

KPI card with the main loan measures.

Loan_Status slicer.

Geography slicer.

Purpose: Identify salary differences across designations while keeping the loan-status and geography context visible.

5. Gender & Marital Status Distribution

This page analyzes the demographic composition of loan customers.

Visuals used:

Donut chart for Gender by count of Loan_ID.

Donut chart for Married by count of Loan_ID.

KPI card with the main loan measures.

Loan_Status slicer.

Geography slicer.

Purpose: Compare the gender and marital-status distribution of the customers represented in the loan dataset.

6. Education & Self-Employment Breakdown

This page examines education level and employment status.

Visuals used:

Pie chart for Education by count of Loan_ID.

Pie chart for Self_Employed by count of Loan_ID.

KPI card with the main loan measures.

Loan_Status slicer.

Geography slicer.

Purpose: Understand the educational and self-employment profile of the loan customer population and analyze it under different filters.

7. Financial Product Ownership

This page studies customer ownership of additional financial or personal assets.

Visuals used:

Column chart for HasCrCard by count of Loan_ID.

Column chart for HasCar by count of Loan_ID.

KPI card with the main loan measures.

Loan_Status slicer.

Geography slicer.

Purpose: Explore customer ownership patterns for credit cards and cars and compare those patterns under selected loan-status and geography filters.

📏 DAX Measures Used

The report contains the following named measures:

Measure

Purpose

M_Total_Customers

Total customer/loan-record KPI used across report pages

M_Loan_Approved

Approved-loan KPI

M_Loan_Not_Approved

Not-approved-loan KPI

M_%_Approved

Approval percentage KPI

M_Max_Salary

Maximum salary measure used for designation analysis

🎛️ Interactive Filtering

The report uses slicers for:

Geography

Loan Status

These filters are placed on the report pages where the corresponding analysis is presented.

📈 Visualization Techniques

KPI Cards

Pie Charts

Donut Charts

Clustered Bar Chart

Column Charts

Combo Chart (Line + Clustered Column)

Scatter Plot

Slicers

💡 Analytical Areas Covered

The dashboard brings together several perspectives of banking loan data in one report:

Loan Outcome → Age → Income & Loan Amount → Geography → Property Area → Salary → Gender → Marital Status → Education → Self-Employment → Credit Card & Car Ownership

📂 Repository Contents

PowerBI-Banking-Loan-Approval/
│
├── POWERBI_BANKING_PROJECT.pbix
├── README.md
└── screenshots/
    └── banking_dashboard.png

🚀 How to Use

Download POWERBI_BANKING_PROJECT.pbix.

Open it using Microsoft Power BI Desktop.

Navigate through the report pages using the page tabs.

Use the available slicers to change the analytical context.

Interact with the visuals to explore the loan data.

🎓 Skills Demonstrated

Power BI dashboard development

Data analysis and visualization

DAX measure creation

Interactive report design

Demographic and financial-data analysis

KPI development

Comparative analysis using filters and multiple visual types

👤 Project

Power BI Banking Loan Approval Analysis
