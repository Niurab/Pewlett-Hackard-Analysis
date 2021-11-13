# Pewlett-Hackard-Analysis

## Overview of the analysis

### Purpose of the analysis

In this study, we determined the number of retiring employees by title and identify employees eligible for participation in the mentorship program.

In the first part of the deliverables, emp_no, first_no and last_name were retrieved from the employees table while the title, from_date and to_date were retrieved from the titles table. The data was filtered on the birth_date column to retrieve employees born between 1952 and 1955, then order by the employee number. The Retirement Titles CSV table was exported and save in the Data folder. Both employees and titles tables were joined on the primary key and filtered by birth_date and the information put in a new table. Unique_titles and retiring were the other 2 tables that were created after using the functions, DISTINCT ON, GROUP BY and ORDER BY.

In the second part of the deliverables, we retrieved columns from both our employees and dept_emp tables, filtered the data on employees born in 1965 who still work for Pewlett Hackard before ordering the table by emp_no.

This report summarizes the analysis and helps prepare Bobby’s manager for what has been tagged the silver tsunami due to the fact that many current employees will reach retirement age soon.

## Results
A. The retirement_titles table provides every employee eligible for retirement as well as how long they have worked in each position since they join Pewlett Hackard.

![retirement_titles](https://user-images.githubusercontent.com/91093413/141611262-f6befa1c-1452-4623-a3fe-cb92a8381668.png)



B. The unique_titles table shows the most recent title for employees in the retirement age.


![unique_titles](https://user-images.githubusercontent.com/91093413/141611287-e2148264-03de-48d7-ae93-b02afa66c6ad.png)


C. The retiring_titles show the employees of retirement age. 64 (57,000 out of the total 90,398) percent of those employees are senior members of the organisation.


![retiring_titles](https://user-images.githubusercontent.com/91093413/141611298-c0814a52-577f-40cc-ad6c-af0f3b564ad6.png)


D. Many of the employees eligible for the mentorship program are senior members of Pewlett Hackard.


![Mentorship_elegibility](https://user-images.githubusercontent.com/91093413/141611308-dafde186-2a1f-4e52-9cfa-9c8d43c8f5fa.png)



## Summary

The fact that 64 percent of all employees are of retirement age indicates that many positions will become vacant in the coming years. Since there will likely not be enough employees in the workforce to occupy these positions is where the mentorship program comes into play. Learning from the retiring employees will enhance the capability of employees that will occupy these positions. Also, the coming generation of employees are more likely to catch up and help the organisation continue the positive trend because of their technology savvy nature.

A total of 1,459 employees are eligible for the mentorship program. This is shown in the table below.

![mentor_count](https://user-images.githubusercontent.com/91093413/141611916-9a71fd42-e606-42ad-8ffb-275a8cbc67d5.png)

The need to find out the number of young employees at Pewlett Hackard and how long they have been in their current position is important and additional queries can be made to find out the number.


----------------------------------------
PostgreSQL 11

pgAdmin 4
