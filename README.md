# SQL :  Employee Database: A Mystery in Two Parts

## Background
It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:
- Data Engineering
- Data Analysis

## Data Modeling
- Inspect the CSVs and sketch out an ERD of the tables. Feel free to use a tool like http://www.quickdatabasediagrams.com.

![image](https://user-images.githubusercontent.com/69765842/103467623-f03fc200-4d1e-11eb-9821-6cef693d36e2.png)

## Data Engineering
- Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.
- For the primary keys check to see if the column is unique, otherwise create a composite key. Which takes to primary keys in order to uniquely identify a row.
- Be sure to create tables in the correct order to handle foreign keys.
- Import each CSV file into the corresponding SQL table. Note be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.

![image](https://user-images.githubusercontent.com/69765842/103467720-caff8380-4d1f-11eb-8b92-f77290917279.png)

![image](https://user-images.githubusercontent.com/69765842/103467722-d18dfb00-4d1f-11eb-8ec9-a09b46ddf652.png)

## Data Analysis
Once you have a complete database, do the following:
- List the following details of each employee: employee number, last name, first name, sex, and salary.
- List first name, last name, and hire date for employees who were hired in 1986.
- List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
- List the department of each employee with the following information: employee number, last name, first name, and department name.
- List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
- List all employees in the Sales department, including their employee number, last name, first name, and department name.
- List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
- In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

![image](https://user-images.githubusercontent.com/69765842/103467778-76a8d380-4d20-11eb-940f-79de292bf076.png)

![image](https://user-images.githubusercontent.com/69765842/103467781-7d374b00-4d20-11eb-8a1f-b56bbef7f458.png)

## Bonus
Generate a visualization of the data by:
- Importing the SQL database into Pandas.
- Create a histogram to visualize the most common salary ranges for employees.

![image](https://user-images.githubusercontent.com/69765842/103467626-fb92ed80-4d1e-11eb-869e-e64dce79942a.png)

- Create a bar chart of average salary by title.

![image](https://user-images.githubusercontent.com/69765842/103467664-575d7680-4d1f-11eb-882b-4f87a30b3941.png)


