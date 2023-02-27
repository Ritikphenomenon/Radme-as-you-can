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

> Insert Record: Allows the user to add a new student record to the array.
> Delete Record: Allows the user to delete a student record from the array by entering the student ID.
> Search Record: Allows the user to search for a student record by entering the student ID.
> Update Record: Allows the user to update a student record by entering the student ID.
> Display Record: Displays all the student records stored in the array.
> Exit: Exits the program.
Each function in the program is described below:

> Build(): This function initializes student details, where the user is first asked for the number of students to enter, and then the user can enter the data of each student respectively.
> Insert(): This function helps in inserting a new student detail into the current table.
> DeleteRecord(): This function takes the input of the student ID from the user and searches for the student in the record. If the student is found, then it passes the index of the student to DeleteIndex() function for deleting the student record.
> SearchRecord(): This function searches for the details of a student in the record using the student ID taken as an input from the user. If the student is found, then it displays the record of the student on the screen.
> DisplayRecord(): This function helps in displaying the details of all students in the record.
> UpdateRecord(): This function searches for a student in the record using the student ID taken as an input from the user. If the student is found, then it updates the new details of the student that are input by the user.
> ShowMenu(): This function displays all available options of the project for the user. From here, the user can navigate to all functions. When the user selects an option from the menu, the program calls a function that performs the selected operation. Each function performs the required operation on the array of structures.
Compiling and Running the Program:

To run the program in a local system, you need a C++ compiler installed on your computer. Follow the steps below to compile and run the program:

> Install a C++ compiler such as GCC, Clang, or Microsoft Visual C++ on your computer.

> Create a new source code file with the extension ".cpp" and copy the above program code into it.

> Save the file and open a command prompt or terminal window.

> Navigate to the directory where you saved the source code file using the 'cd' command.

> Compile the program by entering the command 'g++ filename.cpp' (replace 'filename' with the name of your source code file).

> Once the program is compiled successfully, an executable file will be generated in the same directory.

> Run the program by entering the command './a.out' (on Linux or macOS) or 'a.exe' (on Windows). The program will start running, and you can interact with it using the console input and output.

Bug Description:

The following bugs are present in the program:

> The program allows for duplicate student IDs to be stored, which means that different students could have the same ID. This needs to be fixed to ensure that each student has a unique ID.

> There is a bug in the search function that does not correctly identify and display the student record that matches the entered student ID.

> The update function is not correctly updating the student record with new details entered by the admin. This needs to be fixed.

> The student records are not displayed in a proper order when using the display function.

> When the display function finishes displaying the records, the program terminates instead of returning to the main menu.

> There is a bug in the delete function that is causing student records to not be deleted properly.
