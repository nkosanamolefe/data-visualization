# HR-Dashboard-MySQL-PowerBI

![image](https://github.com/nkosanamolefe/data-visualization/blob/main/HR/HR%20Dashboard.png)

## Tools

**Data** - HR Data with over 22000 rows from the year 2000 to 2020.

**[Data Cleaning](https://github.com/nkosanamolefe/portfolio-projects/tree/main/SQL/HR) & Analysis** - MySQL Workbench

**Data Visualization** - Power BI

## Questions

1. What is the gender breakdown of employees in the company?
2. What is the age distribution of employees in the company?
3. How many employees work at headquarters versus remote locations?
4. What is the average length of employment for employees who have been terminated?
5. How does the gender distribution vary across departments and job titles?
6. Which department has the highest turnover rate?
7. What is the distribution of employees across locations by state?
8. How has the company's employee count changed over time based on hire and term dates?
9. What is the tenure distribution for each department?

## Summary of Findings

1. There are more male employees
2. 5 age groups were created (18-24, 25-34, 35-44, 45-54, 55-64). A large number of employees were between 35-44 followed by 25-34 while the smallest group was 55-64.
3. A large number of employees work at the headquarters versus remotely.
4. The average length of employment for terminated employees is around 8 years.
5. The gender distribution across departments is fairly balanced but there are generally more male than female employees.
6. The Auditing department has the highest turnover rate followed by Legal. The least turn over rate are in the Support, Business Development and Marketing departments.
7. A large number of employees come from the state of Ohio.
8. The net change in employees has increased over the years.
9. The average tenure for each department is about 8 years with Sales having the highest and Product Management having the lowest.having the lowest.

## Limitations

- Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.
