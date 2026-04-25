# Hyundai-Motor-India_vishal_24bco466
Power BI- Project
# Hyundai Motor India — Power BI Project (README)

Key Insights

-SUV / specific models contribute the highest share of total sales.
-Sales distribution varies significantly across states.
-Certain colors show higher customer preference.
-Employee salary varies widely across job roles and levels.
-Sales trends indicate potential seasonal or demand-based patterns.

Business Impact

This dashboard helps identify high-performing products, regional trends, and customer preferences, supporting better strategic and sales decisions

Project Overview

This project showcases a complete **Power BI dashboard** built using a dataset from **Hyundai Motor India**. The goal was to analyze sales performance across various dimensions such as vehicle models, color, gender, state, job roles, transmission types, and employee salary insights.

The dashboard presents a clean, interactive, and visually appealing analytical report that highlights key KPIs, trends, and comparisons.


Key Objectives

* Understand and apply **Data Cleaning**, **Data Shaping**, and **Data Transformation** using **Power Query Editor**.
* Build a professional-level dashboard using **Data Modeling**, **DAX Measures**, and **visualization best practices**.
* Analyse Hyundai Motor India's sales performance using multiple chart types.



Dataset Description

The dataset includes:

* Vehicle Model
* Transmission Type (Automatic / Manual)
* Customer Gender
* State
* Color
* Total Price (Sales)
* Job Level, Job Role, Employee Salary
* Minimum Age
* Maximum sales
* Minimum sales
* Emp_name
* Customer name

  <img width="1920" height="1080" alt="DATASET" src="https://github.com/user-attachments/assets/6eafd56e-b000-416f-8b7d-f84339580a81" />

Data Cleaning (Power Query Editor)

* Removed duplicates
* Handled missing values
* Standardized text formats
* Ensured proper data types (numeric, whole number, text, date, Customer)

   UNCLEANED DATA
<img width="1920" height="1080" alt="UNCLEANED DATA" src="https://github.com/user-attachments/assets/3b7651b3-0c06-4d52-851e-bfb7ddd0f871" />
CLEANED DATA
<img width="1920" height="1080" alt="CLEANED DATA" src="https://github.com/user-attachments/assets/8301f458-d476-4887-ab74-b37dbc8a12ec" />

Data Shaping & Transformation (Power Query Editor)

Transformations Applied:

Modified data types (Date, Whole Number, Decimal Number, Text).
Combined and split columns as needed (e.g., splitting full names).
Used Add Column features:
Conditional columns,Custom formula columns,Date hierarchy fields, Removed irrelevant columns to reduce model complexity. Applied filters to retain only meaningful records. Merged queries or appended tables based on project requirement.
Advanced Power Query Concepts Used:
Applied Steps Query Dependency View Group By Parameter creation (if needed)
Outcome:
A well-structured dataset optimized for modelling.

Data Modelling (Building the Foundation)

Data Modelling Steps:

Identified Fact and Dimension tables. Implemented Star Schema design for high performance.

Created appropriate relationships between tables:
One-to-many (1:), Many-to-one (:1), Configured cross-filter directions. Ensured relationship integrity (no ambiguous paths).

Model Optimization Tasks:
Hid unnecessary columns in report view. Ensured surrogate keys or unique identifiers were used.Avoided unnecessary bi-directional filters.

 Outcome:
A robust and well-structured data model supporting efficient analysis

DAX Measures & Queries Created

Some examples:

* Total Sales
  <img width="1920" height="1080" alt="Total Sales" src="https://github.com/user-attachments/assets/c80783ba-a9f4-456c-bdf9-92eb8cc037ab" />

* Average Sales
  <img width="1920" height="1080" alt="Average sales" src="https://github.com/user-attachments/assets/0edde64a-43cc-4adc-a276-9c36a02b690e" />

* Average Employee Salary
  <img width="1920" height="1080" alt="Average sales" src="https://github.com/user-attachments/assets/3ec46a30-c617-41c8-978a-c9ad3383031c" />

* Models Sold
  <img width="1920" height="1080" alt="Models sold" src="https://github.com/user-attachments/assets/3fdd4aa3-87e4-49ea-bbd8-bbb6044c8cc7" />

* Min age
  <img width="1920" height="1080" alt="Min Age" src="https://github.com/user-attachments/assets/2a947bfe-a071-4456-b333-dc959826cbc6" />
  
* Max sale price
  <img width="1920" height="1080" alt="Max sales price" src="https://github.com/user-attachments/assets/0b6efd31-bac8-46c8-8c9a-0eb8ea5a8817" />

  
* Using functions like: `CALCULATE()`, `DIVIDE()`, `SWITCH()`, `IF()` etc.
  <img width="1920" height="1080" alt="Creta Sales CALCULATE" src="https://github.com/user-attachments/assets/22b4b122-d3a5-4799-b60b-45c73855c69b" />

  <img width="1920" height="1080" alt="High sales IF" src="https://github.com/user-attachments/assets/60fe4293-0483-48ff-8f43-1640ccd4947a" />

  <img width="1920" height="1080" alt="DIVIDE" src="https://github.com/user-attachments/assets/15cab15a-4075-4f2e-b98f-88f2f1ca4c52" />

  <img width="1920" height="1080" alt="rating category SWITCH" src="https://github.com/user-attachments/assets/5548868b-8fe9-42fd-9228-6ff6a7c280f3" />
  
---

Dashboard Features

The dashboard includes:

🔸 KPIs (Cards)

* 118M Total Sales
* 1.31M Average Price
* 97.95K Average Employee Salary
* 5 Models Sold

<img width="1920" height="1080" alt="Main Project DASHBOARD" src="https://github.com/user-attachments/assets/21f07105-876a-4b1c-98c7-9499111fa539" />


🔸 Charts Included

* Bar Charts (Sales by Vehicle Model & Gender)
* Donut Chart (Sum of Total Price)
* Line Chart (Sales by Color)
* Pie Chart (Sales by State)
* Gauge Chart (Total Sales & Minimum Age)
* Matrix Table (Model-wise color distribution & totals)
* Clustered Bar (Employee Salary by Job Role & Level)
* Stacked Area / Line Chart (Sales Trend)



Skills Demonstrated

* Power BI Dashboarding
* Data Cleaning & Shaping
* Data Modeling
* DAX Calculations (Beginner to Intermediate)
* Visual Design & Theme Customization
* Analytical Storytelling

Project 

* Data understanding
* Cleaning & transformation
* Visualization & formatting
* DAX writing
* final dashboard polishing

* Custom theme applied for premium UI
* All visuals made fully interactive

📁 Screenshot Of Main project & Mini project DASHBOARD

The dashboard image is included in the project folder as:
<img width="1920" height="1080" alt="Main Project DASHBOARD" src="https://github.com/user-attachments/assets/f2bf87a2-e53f-40cf-8bf8-e4fc57bf3b49" />

<img width="1920" height="1080" alt="MINI PROJECT DASHBOARD" src="https://github.com/user-attachments/assets/d03955c0-4e24-49b0-bc69-b77d7a0884a8" />

Conclusion

This Power BI project demonstrates strong understanding of business analytics using real-world sales data. It covers essential skills required for analytics roles, including DAX, modeling, and visualization design.
