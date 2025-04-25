# STUDENT PERFORMANCR AND ENGAGEMENT ANALYSIS
Online Course Platform: Student Performance & Engagement Analysis
Dataset Summary
Row Count: 1,200
Columns 
•	Student_ID
•	Name (inconsistencies: all caps, lower case, trailing spaces)
•	Email (some missing or malformed)
•	Gender (Male, M, FEMALE, etc.)
•	Country (India, india, IN, etc.)
•	Age (some missing or invalid)
•	Enrollment_Date (varied date formats)
•	Course_Name
•	Course_Category (e.g., Data Science, Business, etc.)
•	Progress (%) (as strings, some with %, some without)
•	Time_Spent (hrs) (some in minutes, some as text)
•	Completed (Y, Yes, 1 / N, No, 0)
•	Feedback_Rating (1 to 5, some blank, some out of range)
•	Session_Attendance (comma-separated string of session dates)


Part 1: Excel – Advanced Cleaning Tasks

1.	Convert 'Time_Spent' values into hours (handle "30 mins", "1.5", etc.).
2.	Fix invalid/missing 'Age' entries using mean/median imputation.
3.	Extract total sessions attended from the Session_Attendance column.
4.	Filter out invalid email entries and identify duplicates.
5.	Add a flag for "High Performer": Completed == Yes and Rating ≥ 4.
6.	Create new columns: Experience_Level (based on age: Student, Early Career, etc.) Engagement Level (based on Time Spent + Progress)
![image](https://github.com/user-attachments/assets/e361c328-9635-4021-b84d-4d8b596e89eb)
![image](https://github.com/user-attachments/assets/1c123db5-a7d6-461f-981d-12038eb04e2f)
Part 2: Power BI – Advanced Dashboard Tasks
Multi-page dashboard:
•	Overview Page (KPIs, summary)
•	Category Analysis
•	Engagement Heatmap

KPI Cards:
•	Total Students, Avg. Progress, Avg. Rating
•	Course Completion Rate
Bar/Column Charts:
•	Students by Course Category
•	Completion rate by Country
Matrix Table:
•	Cross-tab: Course vs. Feedback Rating
Line/Area Chart:
•	Enrollment trend by month
 Custom Measures (DAX):
•	Completion % by Category
•	Avg. Time Spent per Category
•	Correlation between Progress and Rating (scatter plot)
Drill-through to student details from summary cards.
Use slicers: Course Category, Country, Experience Level


