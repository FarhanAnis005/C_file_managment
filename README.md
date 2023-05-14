# File Management System

This is a simple file management system implemented in C language. It allows the user to create, delete, and modify files. The program has a menu-driven interface and the user can choose the desired option from the menu.

## Functions
The program has three functions:

1. Create a file
This function allows the user to create a new file by providing a filename. The file is created in the current directory. If the file already exists, it will be overwritten.

2. Delete a file
This function allows the user to delete a file by providing a filename. If the file exists, it will be deleted. Otherwise, an error message will be displayed.

3. Modify a file
This function allows the user to modify the contents of a file by providing a filename. If the file exists, the user can enter new content (up to 1000 characters) which will replace the existing content. If the file does not exist, an error message will be displayed.

Usage
To use the program, compile the source code using a C compiler and run the executable. The program will display a menu with the available options. The user can choose an option by entering the corresponding number. If the user chooses an invalid option, an error message will be displayed and the menu will be displayed again.
