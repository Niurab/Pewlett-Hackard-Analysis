# Pewlett-Hackard-Analysis

## Overview of the analysis

Purpose of the analysis

In this study, we determined the number of retiring employees by title and identify employees eligible for participation in the mentorship program.

In the first part of the deliverables, emp_no, first_no and last_name were retrieved from the employees table while the title, from_date and to_date were retrieved from the titles table. The data was filtered on the birth_date column to retrieve employees born between 1952 and 1955, then order by the employee number. The Retirement Titles CSV table was exported and save in the Data folder. Both employees and titles tables were joined on the primary key and filtered by birth_date and the information put in a new table. Unique_titles and retiring were the other 2 tables that were created after using the functions, DISTINCT ON, GROUP BY and ORDER BY.

In the second part of the deliverables, we retrieved columns from both our employees and dept_emp tables, filtered the data on employees born in 1965 who still work for Pewlett Hackard before ordering the table by emp_no.

This report summarizes the analysis and helps prepare Bobby’s manager for what has been tagged the silver tsunami due to the fact that many current employees will reach retirement age soon.

## Results
A. The retirement_titles table provides every employee eligible for retirement as well as how long they have worked in each position since they join Pewlett Hackard.

B. The unique_titles table shows the most recent title for employees in the retirement age.

C. The retiring_titles show the employees of retirement age. 64 (57,000 out of the total 90,398) percent of those employees are senior members of the organisation.

D. Many of the employees eligible for the mentorship program are senior members of Pewlett Hackard.


## Summary

The fact that 64 percent of all employees are of retirement age indicates that many positions will become vacant in the coming years. Since there will likely not be enough employees in the workforce to occupy these positions is where the mentorship program comes into play. Learning from the retiring employees will enhance the capability of employees that will occupy these positions. Also, the coming generation of employees are more likely to catch up and help the organisation continue the positive trend because of their technology savvy nature.


----------------------------------------
PostgreSQL 11

pgAdmin 4
