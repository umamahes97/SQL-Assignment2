# SQL-Assignment2 
## Title :
## Employees Database
### Objective:
To Create the DML commands and execute the queries to given the employees database.

### Employees Database Schema:
Schema represents the structure of the database. It contains the three tables.

Departments
Location
Employees
DML - Data Manipulation Language.
<img width="633" height="383" alt="image" src="https://github.com/user-attachments/assets/cd4f1751-0b6d-43a2-b860-a8b2171aa689" />

<img width="615" height="320" alt="image" src="https://github.com/user-attachments/assets/b069cf25-b198-475c-97a8-47685952c037" />

<img width="654" height="349" alt="image" src="https://github.com/user-attachments/assets/e25616fb-efb9-4661-9e3a-dfd2431a9731" />

<img width="651" height="346" alt="image" src="https://github.com/user-attachments/assets/6b62476d-8f0d-4704-a738-6d37ec93f1f2" />

<img width="621" height="311" alt="image" src="https://github.com/user-attachments/assets/3dace011-e673-4c05-8789-cbfb8392ead8" />

### 1. Distinct Values: 
⦿  a query to retrieve distinct salaries from the Employees table.

<img width="607" height="278" alt="image" src="https://github.com/user-attachments/assets/f5901240-4f97-4829-9e4b-0e4df69868db" />

### 2. Alias (AS): 
⦿  Provide aliases for the "age" and "salary" columns as "Employee_Age" and "Employee_Salary", respectively.

<img width="611" height="312" alt="image" src="https://github.com/user-attachments/assets/f9dc7b5b-d810-47d2-a36d-46be33abb289" />

### 3. Where Clause & Operators: 
⦿  Retrieve employees with a salary greater than ₹50000 and hired before 2016-01-01.

<img width="587" height="267" alt="image" src="https://github.com/user-attachments/assets/9924da20-a214-4566-8e18-dcff16eafbf8" />

⦿  Find the employee whose designation is missing and fill it with "DataScientist". 

<img width="524" height="278" alt="image" src="https://github.com/user-attachments/assets/059923b1-9d22-4c01-9f09-d385476d9b96" />

### Sorting and Grouping Data: 
1. ORDER BY: 
⦿  Find employees sorted by department ID in ascending order and salary in descending order.
<img width="585" height="403" alt="image" src="https://github.com/user-attachments/assets/9f0a5068-09cd-41a2-85d8-c3f4b567f7a9" />

2. LIMIT: 
⦿  Display the first 5 employees hired in the year 2018.

<img width="616" height="339" alt="image" src="https://github.com/user-attachments/assets/9458c03b-a786-473d-8de3-40ecff1567b6" />

3. Aggregate Functions: 
⦿  Calculate the sum of all salaries in the Finance department.

<img width="667" height="285" alt="image" src="https://github.com/user-attachments/assets/31293e20-c145-4849-b794-7ebf3a1bfb51" />

⦿  Find the minimum age among all employees.

<img width="702" height="346" alt="image" src="https://github.com/user-attachments/assets/52df2929-9e63-4ac8-9f69-0a0f19192c62" />

4. GROUP BY: 
⦿  List the maximum salary for each location.

<img width="662" height="300" alt="image" src="https://github.com/user-attachments/assets/b7b2c5e0-1c30-44f7-9078-6ee1605278df" />

⦿  Calculate the average salary for each designation containing the word 'Analyst'. 

<img width="734" height="313" alt="image" src="https://github.com/user-attachments/assets/10e9f2d2-ae0f-4774-b626-ec2dc8a6651b" />

6. HAVING: 
⦿  Find departments with less than 3 employees.

<img width="634" height="264" alt="image" src="https://github.com/user-attachments/assets/91787e51-b40f-442d-8df1-647b0538625e" />

⦿  Find locations with female employees whose average age is below 30.

<img width="663" height="289" alt="image" src="https://github.com/user-attachments/assets/a5d9b703-d9f3-47b4-a74f-a9f3da2b1d91" />

### Joins: 
1. Inner Join: 
⦿  List employee names, their designations, and department names where employees are assigned to a department.

<img width="638" height="339" alt="image" src="https://github.com/user-attachments/assets/142accce-4262-44b6-bc66-54ef2fd5df2f" />

2. Left Join: 
⦿  List all departments along with the total number of employees in each department, including departments with no employees.

<img width="680" height="332" alt="image" src="https://github.com/user-attachments/assets/c5634df6-caf8-4506-a687-3b19a56c7e8b" />

3. Right Join: 
⦿  Display all locations along with the names of employees assigned to each location. If no employees are assigned to a location, display NULL for employee name.

<img width="667" height="331" alt="image" src="https://github.com/user-attachments/assets/86b2e052-01fe-47c3-8b9e-bb3fcba9d922" />















