
# Power BI HR Project

A brief description of what this project does and who it's for

# HR-Dashboard


## Problem Statement

TechnoEdge is a company with employees whose details are stored in the given dataset. The dataset includes various employee attributes such as employee ID, name, position, department, and date of birth, date of joining, experience years, phone number, email, address, salary, gender, marital status, nationality, country, emergency contact details, education qualifications, skills, benefits, and attendance details. With this information, TechnoEdge can track and manage their workforce effectively.

## Objectives

1) To Analyze employee attendance patterns.

2) Identify employee qualifications and skills-Display education qualifications and skills of each employee.

3) Determine the count of employees by department and gender-Use a bar chart to show the count of employees in each department, split by gender.

4) Understand employee experience and salary.

5) Investigate employee age and nationality.

6) Monitor employee performance by position- Use a table to display employee details such as position, name, and sum of salary.

7) Identify employee emergency contacts.

8) Analyze employee turnover rate-Create a line chart to display the count of employees who left each year.



### Data Cleaning

1) To combine multiple tables in Power Query of Power BI, use the "Append Queries" feature and select the relevant tables, ensuring they have the same structure. Renaming tables and organizing them in folders can help with navigation.

2) Used the "Change Type" option in Power Query to alter data types for each column.

3) Utilized the "Replace Values" option in Power Query to edit the Employee Name column to have each word capitalized.

4) Used the "Remove Duplicates" option in Power Query to remove duplicate values from the dataset.

5) Created a conditional column using the "Add Conditional Column" option in Power Query and set the condition to display the level of experience based on the Salary column.

6) Merged the two tables in Power Query using the "Merge Queries" option and match the tables on the Employee ID column.

7) Calculated the age of employees by subtracting their birth date from the current date. Convert the duration to total years and round up the values. Use Power Query functions for data transformation.

8) Accessed the "Transform Data" tab in Power Query and choose the "Date. Year" function to extract the year from a date column.


        
Report Snaps ,

![Capture](https://github.com/Sagarbhar/POWER-BI-HR-1-PROJECT/assets/168229258/f2d1f6e7-7975-4882-a413-a8430755a970)
