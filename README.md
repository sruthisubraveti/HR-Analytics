# HR Analytics Dashboard

This project demonstrates the complete process of building a professional and interactive HR Analytics Dashboard in Power BI, designed to provide the HR department with crucial insights into employee metrics, attrition, and job satisfaction.


**Project Overview:**
The dashboard is built on a dataset comprising nearly 1,500 employee records. The design utilizes a clean, customized gradient background and uniform formatting across all elements, achieving a high level of visual polish.

**Core Features and Visualizations:**
1. Key Metric Tracking: A prominent KPI strip tracks five critical values: Overall Employees, Attrition Count, Active Employees, Average Age, and the calculated Attrition Rate.
2. Job Satisfaction Heat Map: A Matrix chart formatted as a Heat Map visually represents employee job satisfaction ratings (1 to 4) broken down by job role, allowing for rapid identification of roles with low satisfaction.
3. Attrition Analysis: The dashboard includes a Pie Chart detailing Department-wise Attrition, highlighting critical areas like the R&D department where attrition exceeds 50%.
4. Demographic Breakdown: A Stacked Bar Chart displays the distribution of employees by Age Group and Gender, requiring the implementation of a custom sorting column in Power Query to ensure the age groups were correctly ordered (e.g., "Under 25," "25-34," etc.).
5. Detailed Attrition Rate by Age/Gender: To compensate for Power BI's lack of "small multiples" for donut charts, five individual Donut Charts were designed and manually filtered, providing a detailed breakdown of attrition rates by gender across five distinct age groups.
**Technical Execution:**
Extensive data management was performed in Power Query to clean and structure the data. Complex measures were defined using DAX (Data Analysis Expressions) to calculate metrics like attrition rate. A key focus was ensuring robust interactivity: an Education slicer was implemented for high-level filtering, and crucial interactive settings were adjusted across all visuals to ensure clicking on charts performed true data filtering rather than just highlighting. The final result is a powerful tool for data-driven decision-making in HR analytics.

## Tools & Techniques Used
- **Power BI Desktop**: Data visualization and report building
- **Power Query Editor**: Data transformation and cleaning
- **DAX (Data Analysis Expressions)**: Calculated fields and KPIs
- **Excel**: Source data preparation and integration

## Project Files
- `HR Analytics Dashboard.pbix` – The Power BI dashboard file
- `HR Data.xlsx` – Original HR dataset used for analysis

## Key Metrics and Visualizations
- **Attrition Analysis** by age group, gender, department, and job role
- **Employee Distribution** across education fields, business travel frequency, and marital status
- **Performance Metrics** such as years at company, performance rating, work-life balance
- **KPI Tiles** for total employees, attrition %, average working years, and satisfaction index

![image alt](https://github.com/sruthisubraveti/HR-Analytics/blob/45e2a64e2f63ac2d5a738976e5a0549efd768689/HR%20Analytics%20Dashboard.png)
