# studentinfousingfiles
<br>
Author-Rahul
<br>
1 : You are required to create a program in C++ that processes student information stored in a text file
and organizes it using a Linked List.
<br>
<pre>
Requirements:
1. Input File:
o The text file will contain multiple lines of student information.
o Each line will have the following fields separated by whitespace:
 Roll Number (integer)
 Name (string)
 Mobile Number (string)
 Email Address (string)
</pre>
<pre>
2. Linked List:
o Create a Linked List, where each node contains the details of one student.
o The Linked List should be sorted in ascending order based on Roll Number.
3. Program Structure:
o Implement the program using modular design in C++ (use multiple files for different
modules like main.cpp, Student.cpp, LinkedList.cpp, etc.).
</pre>

<pre>
4. Functionality:
o Read data from the text file and populate the Linked List.
o Sort the Linked List based on Roll Number during insertion.
o Display the Linked List content in a user-friendly format.
Additional Instructions:
• Properly handle errors such as missing or improperly formatted input files.
• Use appropriate classes and functions to ensure a clear and modular structure.
• Include comments to explain your code.
Sample Input File:
101 John 9876543210 john@example.com
103 Alice 8765432109 alice@example.com
102 Bob 7654321098 bob@example.com
Expected Output (Linked List Display):
Roll No: 101, Name: John, Mobile: 9876543210, Email: john@example.com
Roll No: 102, Name: Bob, Mobile: 7654321098, Email: bob@example.com
Roll No: 103, Name: Alice, Mobile: 8765432109, Email: alice@example.com
</pre>

<pre>
Implemation details:
Use separate files for each component:
• main.cpp: Program entry point.
• Student.cpp: Define the Student class to store individual student information.
• LinkedList.cpp: Implement the Linked List class and its associated operations.
</pre>
