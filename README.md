# sql-challenge

# Background
It’s been two weeks since I have hired as a new data engineer at Pewlett Hackard (a fictional company). My first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, I designed the tables to hold the data from the CSV files, imported the CSV files into a SQL database, and then answered questions about the data. I had preformed, data modeling, data engineering, and data analysis, respectively in this project.

# Data Modeling
Inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables.

# Data Engineering
Used the provided information to create a table schema for each of the six CSV files. The following I believe has been done:

Specifying the data types, primary keys, foreign keys, and other constraints.

For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.

Created the tables in the correct order to handle the foreign keys.

Imported each CSV file into its corresponding SQL table.

# Data Analysis
List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

# Location of Code 

The location of my code will be found in the EmployeeSQL folder, the schema will be found in the Schema.sql file and the data analysis will be located in the Analysis.sql file. The sketched diagram showing the table relation will be listed as Quick DBD s.PNG. The CSVs where the data was imported from is located in the Data Folder. 

All in all this was a relatively short project. I am looking forward to expanding my knowledge in SQL