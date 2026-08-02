# PowerBI-Student-Performance-Dashboard
📌 Project Overview

This Power BI dashboard analyzes student performance based on attendance, study habits, parental education, internet access, extracurricular activities, and exam scores. The dashboard provides interactive insights using KPIs, charts, slicers, and data modeling.

📊 Dashboard Preview

<img width="1332" height="747" alt="pro dashboard" src="https://github.com/user-attachments/assets/7066f29e-c3d6-41e5-b045-51e24f750cd2" />


🎯 Objectives
Analyze overall student performance
Compare exam scores across grades
Understand attendance trends
Evaluate the effect of parental education
Explore extracurricular participation
Build an interactive dashboard for decision making

🛠 Tools Used
Microsoft Power BI
Power Query
DAX
Data Modeling
Star Schema

📂 Dataset
Student Performance Dataset
[student_performance_dataset.csv](https://github.com/user-attachments/files/30636846/student_performance_dataset.csv)
Total Records: 1000

🔄 ETL Process
Imported CSV dataset
Verified data types
Checked for missing values
Checked duplicates
Created dimension tables
Built star schema
Created DAX measures

📐 Data Model

<img width="1917" height="977" alt="Screenshot 2026-08-02 231332" src="https://github.com/user-attachments/assets/8044ff59-e721-483d-bb44-70ffbb3db23f" />


⭐ DAX Measures

Total Students =
COUNT(student_performance[student_id])

Average Attendance =
AVERAGE(student_performance[attendance_percent])

Average Exam Score =
AVERAGE(student_performance[final_exam_score])

Highest Exam Score =
MAX(student_performance[final_exam_score])

Average Study Hours =
AVERAGE(student_performance[study_time_hours])

📈 Dashboard Features
KPI Cards
Bar Chart
Pie Chart
Donut Chart
Treemap
Interactive Slicers
Cross Filtering

📌 Key Insights

Grade A students have the highest attendance.
More than 80% of students have internet access.
Most students participate in extracurricular activities.
Bachelor's and High School are the most common parental education levels.

📷 Dashboard

<img width="1332" height="747" alt="pro dashboard" src="https://github.com/user-attachments/assets/4c967241-27ec-4df5-94b4-4e9b2d6eb88c" />


🚀 Skills Demonstrated
Data Cleaning
ETL
DAX
Power Query
Data Modeling
Star Schema
Dashboard Design
Data Visualization


