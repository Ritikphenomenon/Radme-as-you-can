Rules:

Each team can participate in only one programming language.

To participate, you must fork this repository, make the necessary changes to the file(s), and then create a pull request (PR) on the main branch with the correct code.

Teams will be ranked based on the time they take to create the PR and the accuracy of their code.

For time-based ranking, only the time taken for the last commit will be considered. Multiple commits can be made in a single PR.

Any commit made after 12 pm will not be considered for any team.

To be ranked based on code, your submitted code must solve all the bugs listed in the project description.

You are allowed to explain your changes using comments.

We hope these rules are clear and easy to follow. Good luck with the contest!

Program Name: Student Management System

Program Description:

This program is designed to manage student records using an array of structures. It allows the user to create, view, search, update, and delete student records.

The program starts by asking the user to enter the number of student records they want to create. The maximum number of records is 20, and if the user enters a number greater than 20, the program limits the number of records to 20.

The user is then presented with a menu that allows them to perform various operations on the student records.

Menu options available:

Insert Record: Allows the user to add a new student record to the array. Delete Record: Allows the user to delete a student record from the array by entering the student ID. Search Record: Allows the user to search for a student record by entering the student ID. Update Record: Allows the user to update a student record by entering the student ID. Display Record: Displays all the student records stored in the array. Exit: Exits the program. Each function in the program is described below:

Build(): This function initializes student details, where the user is first asked for the number of students to enter, and then the user can enter the data of each student respectively.

Insert(): This function helps in inserting a new student detail into the current table.

DeleteRecord(): This function takes the input of the student ID from the user and searches for the student in the record. If the student is found, then it passes the index of the student to DeleteIndex() function for deleting the student record.

SearchRecord(): This function searches for the details of a student in the record using the student ID taken as an input from the user. If the student is found, then it displays the record of the student on the screen.

DisplayRecord(): This function helps in displaying the details of all students in the record.

UpdateRecord(): This function searches for a student in the record using the student ID taken as an input from the user. If the student is found, then it updates the new details of the student that are input by the user.

ShowMenu(): This function displays all available options of the project for the user. From here, the user can navigate to all functions. When the user selects an option from the menu, the program calls a function that performs the selected operation. Each function performs the required operation on the array of structures.


Prerequisite to run the program:

>To run the above Python program on your local system, you would need to have Python installed. Here are the general steps to follow:

>Download and install Python on your local machine. You can download the latest version of Python from the official Python website: https://www.python.org/downloads/

>Open a text editor or an IDE (Integrated Development Environment) such as PyCharm, Visual Studio Code, or Spyder.

>Copy and paste the Python code into the text editor or IDE.

>Save the file with a .py extension, for example, "filename.py".

>Open a command prompt or terminal window and navigate to the directory where you saved the Python file.

>Run the Python program by typing "python filename.py" on the command line and pressing enter.

>The output of the program should be displayed on the console or terminal window.


Bug Description:

The following bugs are present in the program:

The program allows for duplicate student IDs to be stored, which means that different students could have the same ID. This needs to be fixed to ensure that each student has a unique ID.

>There is a bug in the search function that does not correctly identify and display the student record that matches the entered student ID.

>The update function is not correctly updating the student record with new details entered by the admin. This needs to be fixed.

>The student records are not displayed in a proper order when using the display function.

>When the display function finishes displaying the records, the program terminates instead of returning to the main menu.

>There is a bug in the delete function that is causing student records to not be deleted properly.
