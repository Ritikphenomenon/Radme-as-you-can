# Radme-as-you-can
Student Management System :

Descriptions and Features of project:



This is a program for managing student records. It allows the user to create, view, search, update, and delete student records. The program uses an array of structures to store the student records.

The program starts by asking the user to enter the number of student records they want to create. The maximum number of records is 20, and if the user enters a number greater than 20, the program limits the number of records to 20.


The user is then presented with a menu that allows them to perform various operations on the student records. The menu has the following options:




1.    Insert Record: Allows the user to add a new student record to the array.


2.   Delete Record: Allows the user to delete a student record from the array by entering the student ID.


3.   Search Record: Allows the user to search for a student record by entering the student ID.


4.  Update Record: Allows the user to update a student record by entering the student ID.


5.  Display Record: Displays all the student records stored in the array.


6.  Exit: Exits the program.

The program uses a flag variable to indicate whether a student record with the given student ID was found or not.




Working Description :




"This is an overall summary of the program where an admin can build a table of student data, with a maximum of 20 students that can be stored. The following functions are available for the admin to manage the student records:


1. Build(): This function helps in initializing student details, where the admin is first asked for the number of students to enter, and then the admin can enter the data of each student respectively.

2.  Insert(): This function helps in inserting a new student detail into the current table.

3. DeleteRecord(): This works with the help of another function, which is DeleteIndex(). First, DeleteRecord() takes the input of the student ID from the admin and searches for the student in the record. If the student is found, then it passes the index of the student to DeleteIndex() function for deleting the student record.



4. SearchRecord(): This function searches for the details of a student in the record using the student ID taken as an input from the admin. If the student is found, then it displays the record of the student on the screen.



5. DisplayRecord(): This function helps in displaying the details of all students in the record.



6. UpdateRecord(): This function searches for a student in the record using the student ID taken as an input from the admin. If the student is found, then it updates the new details of the student that are input by the admin.



7. ShowMenu(): It displays all available options of the project for the admin. From here, the admin can navigate to all functions. This is one of the main functions of the project. When the user selects an option from the menu, the program calls a function that performs the selected operation. Each function performs the required operation on the array of structures."



Prerequisite to run the program:



To run the program in a local system, you need a C++ compiler installed on your computer. Here are the steps to compile and run the program:

1.Install a C++ compiler such as GCC, Clang, or Microsoft Visual C++ on your computer.


2.Create a new source code file with the extension ".cpp" and copy the above program code into it.


3.Save the file and open a command prompt or terminal window.


4.Navigate to the directory where you saved the source code file using the 'cd' command


5.Compile the program by entering the command 'g++ filename.cpp' (replace 'filename' with the name of your source code file).



Once the program is compiled successfully, an executable file will be generated in the same directory.


Run the program by entering the command './a.out' (on Linux or macOS) or 'a.exe' (on Windows). The program will start running, and you can interact with it using the console input and output.

Bug to Debug :

1.This program have duplicate id for different Name and branch .you have to debug it to , that it can store unique id for
   each student.
   
2.There is Bug in to search a specific student on basis of there id.

3.There is Bug when we try to update the record of any student and this program is not updating the record of any student, which is bug.

4.There is Bug while displaying the record of the students which is not in a proper order.

5.When we try to Displaying record of the student, after displaying program terminate, which is bug.

6.Here Bug is that record of student is not deleted in a proper manner.










