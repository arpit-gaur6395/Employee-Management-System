# Employee-Management-System
  This is my first project on github
 The Employee Management System (EMS) is a desktop application built using Python's Tkinter library for the GUI, MySQL as the database backend, and PIL (Pillow) for image handling. It provides functionalities to manage employee records including adding, viewing, deleting, and displaying employee information. 
 
1.	Login Page: 
o	Users are required to enter a username and password to access the system. o 	Upon successful login (using hardcoded credentials), users are directed to the main page

2.	Main Page: 
o	Employee Information Section: 
▪	Fields for entering employee details such as name, mobile number, email, gender, department, designation, address, experience, and salary. 
▪	Dropdown menus (Combobox) for selecting gender, department, designation, and experience. 
o	Action Buttons: 
▪	Add: Saves the entered employee data to the MySQL database. 
▪	Clear: Clears all input fields. 
▪	Display: Fetches all employee records from the database and displays them in a Treeview widget. 
▪	Delete: Deletes the selected employee record from the database. 
▪	View Information: Populates the input fields with the data of the selected employee for viewing and potential editing. 
3.	Database Operations: 
o	The application connects to a MySQL database (employee_management) hosted locally. 
o	It creates a table (ems) to store employee records if it does not already exist. 
o	Supports insertion, deletion, and retrieval of employee records using SQL queries executed through the MySQL Connector library (mysql.connector). 

