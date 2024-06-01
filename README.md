# Employee_Management_Database_Case_Study
# Overview
This case study involves an employee management system comprising three key tables: LOCATION, DEPARTMENT, and JOB. These tables store information about the locations, departments, and job roles within an organization, respectively. Additionally, there is an EMPLOYEE table containing details about individual employees, including their personal information, job roles, and department assignments.

# Tables and Columns
# 1.LOCATION Table
Columns: Location_ID (Primary Key), City
Description: Stores information about various locations where departments are situated.
# 2.DEPARTMENT Table
Columns: Department_Id (Primary Key), Name, Location_Id (Foreign Key)
Description: Contains details about different departments within the organization, along with their respective locations.
# 3.JOB Table
Columns: Job_ID (Primary Key), Designation
Description: Stores information about different job roles or positions available within the organization.
# 4.EMPLOYEE Table
Columns: Employee_Id (Primary Key), Last_Name, First_Name, Middle_Name, Job_Id (Foreign Key), Hire_Date, Salary, Comm (Commission), Department_Id (Foreign Key)
Description: Stores comprehensive details about individual employees, including their personal information, job roles, hiring dates, salaries, commissions, and department assignments.
# Queries and Analysis
The case study involves writing SQL queries to extract insights and perform analysis on the employee data. Queries may include basic operations such as selection and projection, as well as advanced operations like joins, aggregation, set operations, and subqueries. The goal is to derive valuable insights about the organization's workforce, including employee distributions across departments and locations, salary analysis, hiring trends, and more.
