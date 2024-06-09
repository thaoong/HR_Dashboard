# Human Resources Dashboard
This dashboard is a part of final-term project of Business Intelligence and Decision Support System Course in University of Economics and Law, VNU-HCM.

**Project title:** Business intelligence solution for Human resources department.

**[Data source](https://github.com/thaoong/HR_Dashboard/tree/main/DataSource):** We used the dataset of a fictitious software company called Atlas Labs and built a data warehouse applying SSIS to perform Extract, Transform, Load (ETL).
After conducting ETL, data warehouse is store in MS SQL Server and we used Power BI to load data from this to create dashboard.

**The dashboard inculdes 4 layouts:** 
* Overview of employees
* Employee attrition
* Employee overall performance
* Performance tracker by employee

## Overview of employees
![Screenshot 2024-06-10 002004](https://github.com/thaoong/HR_Dashboard/assets/95263116/6631e336-7aea-4ce3-a883-1b6d28b12dc9)
The Dashboard provides a comprehensive view of employees at Atlas Labs through charts and visual tables with information about the total number of employees, attrition rate, distribution of employees 
by gender, age, job department, marital status, and ethnicity.

## Employee attrition
![Screenshot 2024-06-10 002251](https://github.com/thaoong/HR_Dashboard/assets/95263116/938a0a6f-13ed-4624-95d5-03fa6a95e7e6)
The Attrition dashboard provides an overview of employee attrition at Atlas 
Labs, including interactive charts and tables. It show the attrition rate and total number of employees that have not worked at company anymore. The visual charts provide detailed information on the employee 
attrition rate based on various criteria.

**Based on the dashboard, we can take some key informations about the employee attrition situation of Atlas Labs:**
- Working overtime and frequently business travel probably are the main reason of attrition since 74.25% of churn employees worked overtime and about 25% of them traveled for work frequently.
- Attrition rate are high in 2 positions Sales representative and Recruiter. Based on the chart Total employees and Average Salary by Job Role in Overview dashboard, these are also one of two positions have the lowest salary.

**Some solutions to reduce the attrition rate:**
- Evaluate and adjust the requirements for working overtime, ensuring that the workload does not overload employees.
- Consider flexible working methods such as remote work, flexible hours, or project-based work.
- Enhance support and provide favorable conditions for employees who travel for work.
- Consider adjusting policies related to business travel, such as limiting or fairly distributing business travel assignments and considering the use of technology to reduce the frequency and necessity of travel.

## Employee overall performance
![Screenshot 2024-06-10 002304](https://github.com/thaoong/HR_Dashboard/assets/95263116/4b1d9c44-2857-4926-9eca-a54bb5bd4c23)
The dashboard performance rating provides an overview of the performance and 
satisfaction level of employees with key columns including Self Rating, Manager Rating, Work Life Balance, Training 
Opportunities Taken, Job Satisfaction, Relationship Satisfaction, and Environment Satisfaction displayed by year, department, and rating score.

Based on this, manager can see the overall situation of performance satisfaction level in the whole company. Make comparisions between departments, over the years in order to
take suitable actions.

## Performance tracker by employee
![Screenshot 2024-06-10 002315](https://github.com/thaoong/HR_Dashboard/assets/95263116/38901f0a-cfd3-48fc-9d1a-b3d3fd57d94e)
This dashboard helps businesses track performance indicators of each employee 
over the years. Based on charts, managers can see how employees are 
performing and how their performance has changed over time. They can also understand 
how these indicators affect employee performance.

For example, in the figure above, it shows the performance rating changes over 
the years for employee Abra MacGray. Overall, in 2017, Abra experienced the most 
significant decline in ratings, both in self-assessment and in the assessment by the 
manager. Looking at other indicators, we can see that in 2017, the Work-Life Balance 
61 indicator also experienced the most significant decline, with a value of 2. The employee 
did not rate themselves highly in balancing work and life, which could be the cause of 
the decline in the employee's rating.
