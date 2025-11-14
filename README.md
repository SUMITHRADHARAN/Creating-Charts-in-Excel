# Creating-Charts-in-Excel
This task expands on the previous exercise by focusing on data visualization within Microsoft Excel. Below are the steps to create and label three different chart types using your existing student grades dataset.

Prerequisites
Microsoft Excel: Access to the desktop or web application.
Dataset: The student grades table from the previous task.
Student Name	Math	Science	English	Average
John Doe	85	78	92	85
Jane Smith	90	88	85	87.67
David Lee	72	65	70	69
Mary Williams	88	92	95	91.67
Steps to Complete Task 2
1. Create a Clustered Bar Chart (Comparing Subject Scores)
A bar chart is excellent for comparing scores across different categories (subjects).
Select Data: Highlight the range of cells containing the student names and their subject scores (e.g., cells A1 through D5).
Insert Chart: Go to the Insert tab on the Excel ribbon.
In the Charts group, click the Insert Column or Bar Chart icon and select the first option: Clustered Column.
Label the Chart:
Click the chart title placeholder and type Student Scores by Subject.
Use the + icon next to the chart to add Axis Titles. Label the vertical axis Scores and the horizontal axis Student Names.
Analysis: This chart clearly shows how each student performed relative to their classmates in specific subjects. For instance, Mary Williams consistently scored highest across all three subjects.
2. Create a Pie Chart (Analyzing Subject Proportions)
A pie chart is useful for showing proportions of a whole. We can use it to visualize how much each subject contributes to the total class average.
Calculate Class Averages: In a new area of your spreadsheet (e.g., cells A8:B11), calculate the average for the class for each subject:
A8: Math Average: B8: =AVERAGE(B2:B5)
A9: Science Average: B9: =AVERAGE(C2:C5)
A10: English Average: B10: =AVERAGE(D2:D5)
Select Data: Highlight the labels and the class average scores (cells A8 through B10).
Insert Chart: Go to the Insert tab. Click the Insert Pie or Doughnut Chart icon and select 2-D Pie.
Label the Chart:
Set the title to Class Average Contribution by Subject.
Use the + icon to add Data Labels to display the percentages or exact values on the chart sections.
Analysis: This chart provides a simple visual of which subject had the highest collective score in the class.
3. Create a Line Chart (Tracking Performance Trends - Optional for this data)
Line charts are best for showing trends over time or sequential data. While student grades aren't time series, we can use the "Average" column to quickly visualize performance differences.
Select Data: Highlight the Student Names (A2:A5) and their calculated Averages (F2:F5).
Insert Chart: Go to the Insert tab. Click the Insert Line or Area Chart icon and select the first Line option.
Label the Chart:
Set the title to Student Average Score Comparison.
Add Data Labels to show the exact average score for each point.
Analysis: This chart quickly identifies the top and bottom performers in the class based purely on their overall average score.
