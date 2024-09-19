# Employee Presence Insights Dashboard

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Steps Involved](#steps-involved)
- [Business Insights](#business-insights)
- [Recommendations](#recommendations)
- [Skills Gained](#skills-gained)
- [Dashboard Demo](#dashboard-demo)
- [Conclusion](#conclusion)

## Introduction
This project focuses on analyzing employee presence data from AtliQ Technologies over three months, from April 2022 to June 2022. The primary stakeholders for this analysis are the HR Manager and CEO of AtliQ Technologies. They require insights into the working preferences, attendance, and sick leave percentage of employees to assist in planning team-building activities, product launches, and space utilization strategies. This analysis helps in identifying optimal days when employees are mostly working from the office (WFO) and remotely (WFH), allowing for improved event planning, capacity planning, and space management.


## Project Overview
The dataset consists of three months of employee attendance data, specifically focusing on:
Working Preferences: Work-from-office (WFO) vs. work-from-home (WFH).
Attendance: Overall presence percentage.
Sick Leave Percentage (SL%): Frequency of sick leave usage.
The analysis helps the company optimize scheduling for activities, product launches, and better utilize office space, especially as hybrid work models gain traction. If maintenance work is required in the office, it can be planned for days when fewer employees are present, leading to cost savings on infrastructure.


## Key Features
- **Presence Percentage:** Shows the percentage of employee attendance across three months.
- **Work-from-Home (WFH) Percentage:** Displays the percentage of employees working from home.
- **Sick Leave Percentage (SL%):** Illustrates the percentage of employees taking sick leave.
- **Employee-Specific Analysis:** Allows HR to view detailed insights about individual employees.
- **Monthly and Quarterly Breakdown:** Provides monthly insights for April, May, and June 2022, as well as quarterly trends.
- **Interactive Dashboard:** Slicers and filters are used to drill down into data, making it user-friendly for HR.


## Steps Involved
This project was developed following a structured approach:
1. **Data Collection:** Acquired 3 months of employee attendance data (April 2022 to June 2022). [View Data Source]()
2. **Data Walkthrough:** Conducted an initial exploration of the dataset to understand the structure, key metrics, and the insights the HR team required.
3. **Data Importing:** Imported the collected data into Power BI for further analysis and visualization.
4. **Data Cleaning:** Cleaned the data by merging data from all the sheets, handling missing values and ensuring consistency in the dataset.
5. **DAX Calculations:** Used Data Analysis Expressions (DAX) to calculate key metrics such as Presence %, Work From Home (WFH) %, and Sick Leave (SL) % etc.
6. **Charts Development and Formatting:** Developed various charts including stacked area charts to visually represent employee presence, WFH trends, and sick leave percentages across the months.
7. **Dashboard Development:** Created an interactive dashboard with filters and slicers to enable dynamic analysis of monthly trends. Added a matrix for detailed employee-level insights and used focus mode for deeper analysis.

  
## Business Insights
- **Overall Presence Insights:** The total presence percentage across all three months is 91.83%, with 10.00% working from home and 1.20% taking sick leave.
- **Work Preferences:** Employees tend to work from home the most on Fridays (13.01%) and Thursdays (11.51%), making these days ideal for scheduling maintenance work or flexible hybrid arrangements.
- **Sick Leave Trends:** Sick leave is lowest on Fridays (0.77%), indicating that fewer employees take leave toward the end of the week.
- **Team Activity Planning:** Mondays show the highest presence percentage (93.21%), making them suitable for in-office activities such as team-building events or product launches.
- **Hybrid Work Planning:** The company can effectively plan for hybrid work, with employees working from home for about two days per week and coming into the office for three days, leading to better space utilization.
  
  
## Recommendations
- **Optimize Team Activities:** Plan team-building events, team lunches, or product launches on Mondays or Tuesdays when the majority of employees are working from the office.
- **Hybrid Work Model:** Adopt a hybrid work model where employees work from home on Fridays and Thursdays, allowing for maintenance or infrastructure work on these days.
- **Space Utilization:** Reduce office space requirements by ensuring that employees are provided with laptops and are encouraged to work from home on specific days. This can reduce rental space costs and optimize the use of existing office infrastructure.
- **Sick Leave Monitoring:** Keep track of the rising sick leave trends toward the end of certain months (especially in May and June) and consider implementing wellness programs to mitigate employee health issues.
   
## Skills Gained
Through this project, I gained the following technical and analytical skills:
- **Data Analysis:** Processed and analyzed employee attendance data to derive actionable insights on work preferences, attendance trends, and sick leave patterns.
- **Power BI:** Developed an interactive dashboard using Power BI with features like stacked area charts, slicers for monthly filtering, and detailed employee matrices for granular analysis.
- **DAX & Calculations:** Utilized DAX functions to calculate essential metrics such as Presence %, Work From Home (WFH) %, and Sick Leave (SL) %, enhancing the analytical depth of the dashboard.
- **Dashboard Design:** Crafted a user-friendly and visually appealing dashboard that enables HR managers to quickly filter data, identify patterns, and make informed decisions.


## Dashboard Demo
You can find a screenshot showcasing the sales analysis and key insights here:

![Dashboard Screenshot 1](https://github.com/KomalSharma0/AtliQ-Hardware-Sales-Analysis/blob/main/AtliQ%20Sales%20Dashboard1.png)
![Dashboard Screenshot 2](https://github.com/KomalSharma0/AtliQ-Hardware-Sales-Analysis/blob/main/AtliQ%20Sales%20Dashboard2.png)
![Dashboard Screenshot 3](https://github.com/KomalSharma0/AtliQ-Hardware-Sales-Analysis/blob/main/AtliQ%20Sales%20Dashboard3.png)
![Dashboard Screenshot 4](https://github.com/KomalSharma0/AtliQ-Hardware-Sales-Analysis/blob/main/AtliQ%20Sales%20Dashboard4.png)

Alternatively, you can view the dashboard [here](https://github.com/KomalSharma0/AtliQ-Hardware-Sales-Analysis/blob/main/AtliQ%20Hardware%20Sales%20Dashboard.pbix).

## Conclusion
This project was created as a guided HR analytics project using Power BI, with reference to the Codebasics YouTube channel. The analysis provides actionable insights that help AtliQ Technologies optimize team-building activities, work-from-home arrangements, and space utilization. By implementing the insights gained, AtliQ Technologies can plan more efficiently and reduce costs associated with office space and infrastructure.



