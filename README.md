Basic Calculator using Tkinter
Introduction
This project is a Basic Calculator built using Python's Tkinter module. The calculator provides a simple graphical user interface (GUI) where users can perform basic arithmetic operations such as addition, subtraction, multiplication, division, and exponentiation (power).

Features
User-friendly interface with a numeric keypad.
Supports basic arithmetic operations: +, -, *, /, and pow.
A clear button to reset the input field.
An exit button to close the application.
Technologies Used
Python 3.x
Tkinter (for GUI)
How It Works
The application creates a Tkinter window (root), which serves as the main interface.
An Entry widget (e) is used to display user input and results.
Buttons are created for numbers (0-9) and operators (+, -, *, /, pow).
Clicking a number button appends the number to the entry field.
Clicking an operator button stores the first number and operation type.
Clicking = performs the calculation based on the stored values and displays the result.
Clicking clear resets the input field.
Clicking exit closes the application.
Code Breakdown
buttonclick(number): Appends the clicked number to the entry field.
clear(): Clears the entry field.
buttonadd(), sub(), mul(), div(), pow(): Store the first number and the operation type.
equal(): Computes and displays the result.
