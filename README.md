Tkinter Calculator

Overview

This is a simple GUI-based calculator application built using Python and the Tkinter library. 
The calculator allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.
It features a clean and user-friendly interface with buttons for digits (0-9), arithmetic operations, a decimal point, an equals button, and a clear button.

Features

  * Basic arithmetic operations: Addition (+), Subtraction (-), Multiplication (*), and Division (/)

  * Graphical user interface: Built using Tkinter for ease of use

  * Error handling: Prevents crashes from division by zero or syntax errors

  * Clear function: Allows resetting the input field

  * Live updates: Displays the current expression as the user inputs values

Requirements:

Ensure you have Python installed on your system. This program requires no additional dependencies beyond the built-in Tkinter module.

Installation & Usage:

  1. Clone or download the script.

  2. Run the script using Python:
```python calculator.py```

  3. The calculator window will open, allowing you to input numbers and operations using the provided buttons.

Code Explanation:

  * button_press(num): Updates the display when a number or operator button is pressed.

  * equal(): Evaluates the entered mathematical expression and displays the result.

  * clear(): Clears the current input.

  * GUI Elements:

    * A label displays the current input and results.

    * A grid layout is used for digit and operator buttons.

    * The clear button resets the display.

Known Issues:

  * The application does not support keyboard input; only button clicks work.

  * Does not implement advanced operations like parentheses, exponents, or memory functions.

Future Improvements:

  * Add keyboard support for user input.

  * Implement additional mathematical operations.

 * Improve the UI with themes or styling options.

