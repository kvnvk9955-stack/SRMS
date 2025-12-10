Student Record Management System (SRMS):
The Student Record Management System (SRMS) is a simple C-based console application that manages student information using file handling. It includes a role-based login system with separate access levels for Admin, Staff, User, and Guest. The program allows different operations depending on the user role and provides a clean, menu-driven interface suitable for academic mini-projects and learning purposes.

How It Works:
The system reads login details from a credentials.txt file.
Student data is stored and managed through a students.txt file.
Each role sees a different menu and set of permissions.
Admin has full control, while others have limited access.

Technologies Used:
C Programming

File Handling:
Structures
Basic Authentication Logic

File Requirements:
Make sure your project directory has

students.txt
credentials.txt

Example credentials file:

admin admin123 ADMIN
staff1 staff123 STAFF
user1 user123 USER
guest guest GUEST

How to Run:

Compile the program using any C compiler:
gcc srms.c -o srms

Run the executable:
./srms

Sample Features:
Login authentication
Add, view, search, update, delete student records
Role-based permissions
Menu-driven interface

Ideal For:
College mini-projects
File handling practice
Structure and menu-driven program learning
Demonstrating basic login-based systems

Author: Kolli Venkata Naga Vamsi Krishna
SRM AP-UNIVERSITY 
