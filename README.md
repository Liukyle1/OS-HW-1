# Homework 1 for opertaing systems

## A fully functional exmaple of a code that executes shell or system commands in a given menu.
This project uses these following shell commands:
• dir (list directory contents, Windows equivalent of ls)
• cd (print directory)
• mkdir (create a new directory)
• echo (display a message)
• type (concatenate and display content of files, Windows equivalent of cat)

## User instructions
Lets see how this code will run on a windows enviroment!
* When the code is running the terminal will output a display menu with these options:
  1. List directory contents
  2. Print working directory
  3. Create a new directory
  4. Display a message
  5. Concatenate and display content of a file
  6. EXIT
* When the display menu is popped up, the user will have to input a number 1-6
* When clicking the 1st option the terminal will output the current directory contents
* When clicking the 2nd option the terminal will print the working directory
* When clicking the 3rd option the system command will create a new directory named new_folder(if their exists such a directory the program will fail to create a new directory as their already exists one)
* This also uses the system command to delete an existing directory named "old_folder" (if such existing directory doesnt exist the program will output the message "unable to delete existing directory")
* When clicking the 4th option the system yses the shell command "echo" to display the message "Hello welcome to Operating systems, Hope you're ready!" and then outputs "command executed successfully" when the message is displayed correctly and vice versa if it fails
* When clicking the 5th option the user would have to input the name of the file they would like to display, the program then uses the shell command "type" to search for the file to concatenate and display the file and its content.
* If there is no such file then the program will pop up an error message
* Option 6 is pretty self explanatory, when the user wants to exit they would choose option 6.
* In the case of a user inputting anything that isn't 1-6 the program will notice this and then loop back, so the menu will pop up again.
* The program also loops the display menu until the user chooses to exit.

## User Warnings
* Please make sure you are in the Windows OS, or the code will not work accordingly as it is tailored to a Windows operating system
* If you are not in a Windows OS then the user could tweak the code to their operating system of choice
