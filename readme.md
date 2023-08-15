# Data Modeling, Data Engineering and Data Analysis using SQL (SQL Server)

The project involves analyzing employee data from a fictional company named Pewlett Hackard. The provided dataset includes information about employees' names, IDs, titles, department details, salaries, birth dates, genders, and hire dates.

## Data Modeling

For data modeling, I've designed an Entity Relationship Diagram (ERD) using the QuickDBD tool. The ERD showcases the relationships between different entities and their attributes.
[QuickDBD-export.pdf](https://github.com/RahiemBrooks/SQL-Challenge/files/12346797/QuickDBD-export.pdf)

![QuickDBD-export](https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/49d26751-d1a1-4120-b7b8-694ae6ff9b02)


<img width="835" alt="erd" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/36368f7b-fa7d-4770-a491-106ab3c1e40b">

## Data Engineering

In the data engineering phase, I've created SQL scripts to build the necessary tables, set primary keys, foreign keys, and constraints. The SQL code can be found in the [employees_schema.sql](sql/employees_schema.sql) file.

## Data Analysis

Data analysis is performed to answer specific questions using SQL queries. The analysis results, along with screenshots, are presented in the [Query Images folder](screenshots/query/).

- **Question 1:** List employee details with employee number, last name, first name, sex, and salary.
 <img width="484" alt="q1" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/51c92031-9bcf-435f-be9b-e2cc341f48f1">

- **Question 2:** List first name, last name, and hire date for employees hired in 1986.
 <img width="293" alt="q2" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/3771d3c5-338f-49ad-b419-30096a98741d">

- **Question 3:** List the manager of each department along with relevant details.
 <img width="452" alt="q3" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/1a7b84f5-7782-46cd-b4ed-e94c30007fad">

- **Question 4:** List department number along with employee details.
  <img width="567" alt="q4" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/0de5da28-76c4-48a3-bca1-12372a0a6a73">

- **Question 5:** List employees named Hercules with specific criteria.
 <img width="339" alt="q5" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/4457e5bb-1928-442d-8768-b52c703e8371">

- **Question 6:** List employees in the Sales department.
  <img width="418" alt="q6" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/b2d31dd7-1ab9-4549-821f-8cf8b65b9d3b">

- **Question 7:** List employees in the Sales and Development departments.
 <img width="417" alt="q7" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/a4bd1fd0-c329-473b-a518-6fedaa245ba3">

- **Question 8:** List frequency counts of employee last names.
<img width="212" alt="q8" src="https://github.com/RahiemBrooks/SQL-Challenge/assets/135518113/8c821be1-7410-4654-a24c-3d3154bf1bcf">
