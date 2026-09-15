


 Student Performance Analysis Dashboard






 Project Overview
This project analyzes 1,000,000 student records to understand academic performance and the relationship between students' study habits, attendance, class participation, and final scores.

The project combines Python exploratory data analysis (EDA) with an interactive Power BI dashboard to transform raw student-performance data into clear, decision-ready insights.

The analysis focuses on:

Overall student performance

Grade distribution

Average total score

Weekly self-study hours

Attendance percentage

Class participation

Relationship between study time and academic performance

Relationship between attendance and academic performance

 Business / Analytical Objectives
The main objectives of this project are to:

Measure the overall academic performance of students.

Identify how students are distributed across grades.

Determine the average score and other key performance indicators.

Investigate whether self-study time is associated with higher scores.

Examine whether attendance is associated with total score.

Create an interactive dashboard that allows users to filter performance by grade.

Present findings in a format suitable for educators, school administrators, and other stakeholders.

 Dataset
Dataset: student_performance.csv

Records: 1,000,000 students

Columns: 6

Column	Description
student_id	Unique identifier for each student
weekly_self_study_hours	Average number of hours spent studying independently each week
attendance_percentage	Student attendance percentage
class_participation	Class participation score
total_score	Overall student performance score
grade	Student grade category
Data Quality
The dataset was inspected for:

Number of rows and columns

Data types

Missing values

Duplicate records

Descriptive statistics

Unique grade categories

Minimum and maximum values

 Tools & Technologies
Python
Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy

Jupyter Notebook

Power BI
Power Query

DAX

KPI Cards

Clustered Column Charts

Scatter Charts

Slicers

Interactive dashboard design

Version Control
Git

GitHub

 Project Workflow
Raw Dataset
     ?
Data Inspection
     ?
Data Cleaning & Validation
     ?
Exploratory Data Analysis
     ?
Statistical Analysis
     ?
Power BI Data Preparation
     ?
DAX Measures
     ?
Interactive Dashboard
     ?
Insights & Recommendations
 Key Performance Indicators
The Power BI dashboard contains four main KPI cards:

1. Total Students
1,000,000

2. Average Total Score
84.28

3. Average Attendance
84.71%

4. Average Weekly Self-Study
15.03 hours

These KPIs provide a quick summary of the student population before users explore the detailed visuals.

 Power BI Dashboard Visualizations
The dashboard contains the following visuals:

1. Student Distribution by Grade
A column chart showing the number of students in each grade category.

Grade	Students
A	548,644
B	258,174
C	141,980
D	44,998
F	6,204
Key observation: Grade A represents the largest student group, while Grade F represents the smallest.

2. Average Score by Grade
This visualization compares average total scores across grade categories.

Grade	Average Score
A	96.04
B	77.95
C	63.56
D	49.38
F	35.47
The visual makes the performance gap between grade categories easy to identify.

3. Study Hours vs Total Score
A scatter plot compares weekly self-study hours with total score.

The dataset shows a strong positive correlation of approximately:

0.812

This indicates that students who spend more time on self-study generally tend to achieve higher total scores.

Analytical insight: Self-study hours are the strongest linear predictor of total score among the numeric variables in this dataset.

4. Attendance vs Total Score
A scatter plot compares attendance percentage with total score.

The correlation is approximately:

-0.001

This indicates virtually no linear relationship between attendance percentage and total score in this particular dataset.

Important: This does not mean attendance is unimportant in education. It means that within this dataset, attendance alone does not explain variation in total scores through a simple linear relationship.

5. Grade Slicer
An interactive Power BI slicer allows users to filter the dashboard by:

A

B

C

D

F

Selecting a grade updates the KPI cards and visualizations dynamically.

 Key Insights
Insight 1 — Overall performance is relatively high
The average total score is approximately 84.28, indicating a generally strong overall performance across the dataset.

Insight 2 — Grade A dominates the dataset
More than half of the students are classified as Grade A:

548,644 out of 1,000,000 students (54.86%)

Insight 3 — Study time has a strong relationship with performance
Weekly self-study hours have a correlation of approximately 0.812 with total score.

This is a strong positive relationship and suggests that independent study time is strongly associated with academic performance in this dataset.

Insight 4 — Attendance shows almost no linear relationship with score
Attendance has a correlation of approximately -0.001 with total score.

This is a useful example of why analysts should investigate the data rather than assume that every commonly expected factor will show a strong statistical relationship.

Insight 5 — Class participation has almost no linear relationship with total score
Class participation has a correlation of approximately 0.001 with total score in the dataset.

Again, this describes the observed data and should not be interpreted as proof that classroom participation has no educational value.

 Power BI DAX Measures
The dashboard uses measures such as:

Total Students = COUNTROWS(student_performance)
Average Score = AVERAGE(student_performance[total_score])
Average Attendance = AVERAGE(student_performance[attendance_percentage])
Average Study Hours = AVERAGE(student_performance[weekly_self_study_hours])
Average Participation = AVERAGE(student_performance[class_participation])
These measures allow the dashboard to respond dynamically to filters and slicer selections.

 Recommendations
Based on the analysis:

Encourage structured self-study programs because study hours show a strong positive association with total score.

Monitor students with low study hours and provide targeted academic support.

Use interactive dashboards to identify performance patterns across different grade groups.

Avoid relying on assumptions alone. Statistical analysis should be used to test whether factors such as attendance and participation actually show meaningful relationships with performance.

Combine multiple indicators when evaluating student performance rather than using a single metric.

 Dashboard Preview
Add your Power BI dashboard screenshot to the repository and display it here:

![Student Performance Power BI Dashboard](images/student-performance-dashboard.png)
Recommended repository structure:

Student-Performance-Analysis/
¦
+-- README.md
+-- data/
¦   +-- student_performance.csv
¦
+-- notebooks/
¦   +-- student_performance_analysis.ipynb
¦
+-- powerbi/
¦   +-- Student_Performance_Dashboard.pbix
¦
+-- images/
¦   +-- student-performance-dashboard.png
¦
+-- requirements.txt
 Skills Demonstrated
This project demonstrates practical skills in:

Data cleaning

Data validation

Exploratory Data Analysis (EDA)

Statistical analysis

Correlation analysis

Data visualization

Python programming

Pandas and NumPy

Matplotlib and Seaborn

Power Query

DAX

KPI development

Dashboard design

Data storytelling

Business insight generation

GitHub portfolio development

 Conclusion
The Student Performance Analysis project demonstrates an end-to-end data analytics workflow, from raw data inspection to statistical analysis and interactive business intelligence reporting.

The strongest finding is the relationship between weekly self-study hours and total score, while attendance and class participation show almost no linear correlation with total score in this dataset.

The project demonstrates how a Data Analyst can move beyond simply creating charts and use data to answer meaningful questions, identify patterns, communicate insights, and support evidence-based decision-making.

 Author
Babajide John Falowo

Data Analyst | Data Science Enthusiast

Skills
Python • SQL • Power BI • Tableau • Excel • Statistics • Data Visualization

Connect With Me
GitHub: https://github.com/singleme92

LinkedIn: https://www.linkedin.com/in/babajide-falowo-a59456281

 If you find this project useful, feel free to explore the repository and connect with me on GitHub or LinkedIn.
