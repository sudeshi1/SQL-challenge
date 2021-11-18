# SQL-challenge - Employee Database: A Mystery in two parts

## Background

The first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.
In this project, design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. 

#### Tasks Overview:

1. Data Engineering
2. Data Analysis

## Data Modelling

Inspected the CSVs and sketched out an ERD of the tables. 
Tool used: http://www.quickdatabasediagrams.com

![ERD](/images/Data_Model.png)

## Data Engineering

- Created a table schema for each of the six CSV files and specified data types, primary keys, foreign keys, and other constraints.
- Imported each CSV file into the corresponding SQL table

## Data Analysis

### Tasks

1. List the following details of each employee: employee number, last name, first name, sex, and salary.
2. List first name, last name, and hire date for employees who were hired in 1986.
3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
4. List the department of each employee with the following information: employee number, last name, first name, and department name.
5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
6. List all employees in the Sales department, including their employee number, last name, first name, and department name.
7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
