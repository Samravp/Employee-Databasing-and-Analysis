# Pewlett Hackard Employee Database

For this project, I designed a SQL database to hold the historial employee records of the Pewlett Hackard Corporation.

This project was performed in three steps;

1. Data Engineering/Data Modelling;

2. Data Analysis; and

3. Data Visualisation.


#### Data Engineering

Firstly, historical CSV records were inspected and and ERD of the tables were sketched out, I utilised [http://www.quickdatabasediagrams.com](http://www.quickdatabasediagrams.com) for this purpose.

I was able to initialise the tables in PostgreSQL by exporting the information and the SQL query from quickdatabasediagrams.com.

#### Data Analysis

After imported the CSV files into the relavant tables in the database, the following queries were completed;

1. Listed following details of each employee: employee number, last name, first name, sex, and salary.

2. Listed first name, last name, and hire date for employees who were hired in 1986.

3. Listed the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. Listed the department of each employee with the following information: employee number, last name, first name, and department name.

5. Listed first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B".

6. Listed all employees in the Sales department, including their employee number, last name, first name, and department name.

7. Listed all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. Listed the frequency count of employee last names, i.e., how many employees share each last name in descending order.

## Data Visualisation

To generate a visualisation of the data, I followed below steps;

1. Imported the SQL database into Pandas.

2. Created a histogram to visualise the most common salary ranges for employees.

3. Created a bar chart of average salary by title.

