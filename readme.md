# Data Modeling, Data Engineering and Data Analysis using SQL (SQL Server)

The project involves analyzing employee data from a fictional company named Pewlett Hackard. The provided dataset includes information about employees' names, IDs, titles, department details, salaries, birth dates, genders, and hire dates.

## Data Modeling

For data modeling, I've designed an Entity Relationship Diagram (ERD) using the QuickDBD tool. The ERD showcases the relationships between different entities and their attributes.

![Entity Relationship Diagram](screenshots/erd/QuickDBD-export.png)

The ERD image can be found in the [ERD folder](screenshots/), along with the code used to generate it.

## Data Engineering

In the data engineering phase, I've created SQL scripts to build the necessary tables, set primary keys, foreign keys, and constraints. The SQL code can be found in the [employees_schema.sql](sql/employees_schema.sql) file.

## Data Analysis

Data analysis is performed to answer specific questions using SQL queries. The analysis results, along with screenshots, are presented in the [Query Images folder](screenshots/query/).

- **Question 1:** List employee details with employee number, last name, first name, sex, and salary.
  ![Question 1 Result](screenshots/query/q1.PNG)

- **Question 2:** List first name, last name, and hire date for employees hired in 1986.
  ![Question 2 Result](screenshots/query/q2.PNG)

- **Question 3:** List the manager of each department along with relevant details.
  ![Question 3 Result](screenshots/query/q3.PNG)

- **Question 4:** List department number along with employee details.
  ![Question 4 Result](screenshots/query/q4.PNG)

- **Question 5:** List employees named Hercules with specific criteria.
  ![Question 5 Result](screenshots/query/q5.PNG)

- **Question 6:** List employees in the Sales department.
  ![Question 6 Result](screenshots/query/q6.PNG)

- **Question 7:** List employees in the Sales and Development departments.
  ![Question 7 Result](screenshots/query/q7.PNG)

- **Question 8:** List frequency counts of employee last names.
  ![Question 8 Result](screenshots/query/q8.PNG)
