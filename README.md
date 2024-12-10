# HR-Analytics
Used POWER BI and created an HR analytics dashboard that provides insights into employee demographics, Attrition rates, hiring trends, performance metrics, and satisfaction scores to improve HR decision-making.

We have the following sample dataset in CSV format: [HRDataset_v14.csv](https://github.com/shivam43430/HR-Analytics/blob/main/HRDataset_v14.csv). The data is clean and properly formatted.

Connect to Data Sources: Load the CSV files into POWER BI.
Go to Data > Connect to Data > Text File and select your CSV files.

Dashboard Layout:
● Main Dashboard Overview:
○ KPIs: Total Employees, Turnover Rate, Average Performance Score, Average
Satisfaction Score.
○ Links to detailed dashboards: Demographics, Turnover, Hiring, Performance,
Satisfaction.

Creating Visualizations in Tableau
1. Employee Demographics Dashboard:

Age Distribution: Create a histogram.
tableau

Copy code
1. Drag `Age` to Columns.

2. Drag `Number of Records` to Rows.

3. Change the mark type to `Bar`.

○

Gender Distribution: Create a pie chart.
tableau
Copy code
1. Drag `Gender` to Columns.

2. Drag `Number of Records` to Rows.

3. Change the mark type to `Pie`.

4. Drag `Gender` to Color.

○

Department Distribution: Create a bar chart.
tableau
Copy code
1. Drag `Department` to Columns.

2. Drag `Number of Records` to Rows.

3. Change the mark type to `Bar`.

○
2. Employee Turnover Dashboard:

Turnover Rate: Create a line chart.
tableau
Copy code
1. Drag `HireDate` to Columns.

2. Drag `Turnover Rate` (calculated field) to Rows.

3. Change the mark type to `Line`.

○

Termination Reasons: Create a bar chart.
tableau
Copy code
1. Drag `Termination Reason` to Columns.

2. Drag `Number of Records` to Rows.

3. Change the mark type to `Bar`.

○
3. Hiring Trends Dashboard:

Hiring Rate: Create a line chart.
tableau
Copy code
1. Drag `ApplicationDate` to Columns.

2. Drag `Hiring Rate` (calculated field) to Rows.

3. Change the mark type to `Line`.

○

Source of Hire: Create a bar chart.
tableau
Copy code
1. Drag `Source` to Columns.

2. Drag `Number of Records` to Rows.

3. Change the mark type to `Bar`.

○

Time to Fill: Create a bar chart.
tableau
Copy code
1. Drag `PositionApplied` to Columns.

2. Drag `Time to Fill` (calculated field) to Rows.

3. Change the mark type to `Bar`.

○
4. Performance Metrics Dashboard:

Performance Scores: Create a scatter plot.
tableau
Copy code
1. Drag `ReviewDate` to Columns.

2. Drag `PerformanceScore` to Rows.

3. Change the mark type to `Circle`.

4. Drag `EmployeeID` to Detail.

○

Top Performers: Create a leaderboard.
tableau
Copy code
1. Drag `PerformanceScore` to Rows.

2. Drag `EmployeeID` to Columns.

3. Sort by `PerformanceScore`.

○
5. Employee Satisfaction Dashboard:

Satisfaction Scores: Create a line chart.
tableau
Copy code
1. Drag `SurveyDate` to Columns.

2. Drag `SatisfactionScore` to Rows.

3. Change the mark type to `Line`.
