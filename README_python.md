# Radme-as-you-can
Student Management System :

Descriptions and Features of project:

This is a program for managing student records. It allows the user to create, view, search, update, and delete student records. The program uses an array of structures to store the student records.

The program starts by asking the user to enter the number of student records they want to create. The maximum number of records is 20, and if the user enters a number greater than 20, the program limits the number of records to 20.
The user is then presented with a menu that allows them to perform various operations on the student records. The menu has the following options:
Insert Record: Allows the user to add a new student record to the array.
Delete Record: Allows the user to delete a student record from the array by entering the student ID.
Search Record: Allows the user to search for a student record by entering the student ID.
Update Record: Allows the user to update a student record by entering the student ID.
Display Record: Displays all the student records stored in the array.
Exit: Exits the program.

The program uses a flag variable to indicate whether a student record with the given student ID was found or not.

Working Description :

It is overall summary Where Admin can Build The Table of student data and maximum 20 students can 
only be stored:

1.Admin Can entered Data like Name, Student Id, Branch, Batch and Age of the student.
a)build():This functions help in intialising students details in which admin is first asked for number of students to enter and than admin can enter the data of
student respectively.
b)Insert(): this functions help in inserting new student detail  in current table.

c)deleteRecord():This works  with help of another function , which is deleteIndex().  in this first deleteRecord() takes the
input of student id from the admin and search the student in the record . if the student is found than it passes the index of student in 
deleteIndex() functions for deleting the student record.

d)searchRecord():This functions search the details of a student in the record using student id which is taken as an input from admin and if the student is
found then is display the record of student in the screen.

e)Displayrecord():this functions helps in displaying details of all student in the record.

f)updateRecord(): This functions search a student in the record using student id which is taken as an input from admin and if the student is
found then updating new details of the student which is input by the admin.

g) showMenu(): it display the all available options of the project for the admin. from here admin can navigate to all functions, it is one of the main functons of the project.When the user selects an option from the menu, the program calls a function that performs the selected operation. Each function performs the required operation on the array of structures.


Prerequisite to run the program:

a)To run the above Python program on your local system, you would need to have Python installed. Here are the general steps to follow:
b)Download and install Python on your local machine. You can download the latest version of Python from the official Python website: https://www.python.org/downloads/
c)Open a text editor or an IDE (Integrated Development Environment) such as PyCharm, Visual Studio Code, or Spyder.
d)Copy and paste the Python code into the text editor or IDE.
e)Save the file with a .py extension, for example, "filename.py".
f)Open a command prompt or terminal window and navigate to the directory where you saved the Python file.
g)Run the Python program by typing "python filename.py" on the command line and pressing enter.
h)The output of the program should be displayed on the console or terminal window.










