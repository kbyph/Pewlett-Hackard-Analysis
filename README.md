# Pewlett Hackard Analysis

## Overview of Project
The purpose of this project is to conduct a Database analysis for Pewlett Hackard pertaining information on the number of future retirees within all departments in order to prepare a plan to hire new staff and fill in empty positions. 

The analysis was based on two factors: the birth dates ranging from 1952 to 1955 and hired dates from 1985 to 1988.

## Resources
- Software:
  - SQL
  - PostgreSQL
  - pgAdmin 4
  - Visual Studio Code
  - QuickDBD

- Orginal datasets:
  - departments.csv
  - dept_emp.csv
  - dept_manager.csv
  - employees.csv
  - salaries.csv
  - titles.csv

## Results
Data extraction from the provided datesets allows us to create four new tables that display each employee retiring and their eligibility status for the mentorship program. 

- Retirement Titles
![image](https://user-images.githubusercontent.com/102638461/171081270-22d95843-c048-45c6-9155-28dd993d8373.png)
  - The retirement titles table allows us to see which employees were born between  01-01-1952 through 12-31-1955.
  
- Unique Titles
![image](https://user-images.githubusercontent.com/102638461/171081179-67ea5b46-0950-48df-b02b-3db66cd2c15d.png)
  - The unique titles table is the same table as above with different filters that descends the employee number order and filters out who already left the company. 
  
- Retiring Titles
![image](https://user-images.githubusercontent.com/102638461/171080824-7804ac86-ab72-46fe-8ae5-b28582a2bf43.png)
  - The retiring titles table tallies up the number of employees in each category in descending order. As we can see here, there are 90,398 total employees that are within retirement age, with most of the positions being at senior status.

- Mentorship Eligibility
![image](https://user-images.githubusercontent.com/102638461/171081017-9c20998e-b6dc-4376-8576-7c2f5fe42a02.png)
  - The mentorship eligibility table shows which employees are candidates for the mentorship program. Majority of these workers are at a senior status in comparison to the rest of the company.
 
## Summary
Due to the fact that more than half of the company will retire soon, there are a lot of vacant positions to be filled within the next upcoming years. However, there are a good amount of employees that are potential candidates for the mentorship eligibility program that hold senior positions whom are very capable of leading the next generation of workers to follow. With more workers retiring each year, there must be a significant efforts to restore enough empty slots to keep the company producing at it's highest potential.
