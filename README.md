Calculator Web Application
This is a simple and functional calculator web application with advanced mathematical functions. The calculator includes basic operations, as well as advanced functions like percentage (%), factorial (!), power (e^x), and mathematical constants such as π.

Features
Basic Arithmetic Operations: Addition, subtraction, multiplication, division, and decimal support.
Advanced Functions:
Percentage (%)
Factorial (!)
Exponentiation (e^x)
π (Pi)
Parentheses for complex expressions
Keyboard Support: Use both on-screen buttons and the keyboard to enter values and operators.
History: Tracks all performed calculations with their results.
Installation
Clone or download this repository to your local machine.
Open the index.html file in your preferred browser to use the calculator.
Files Included
index.html: Main HTML structure of the calculator.
style.css: Stylesheet that defines the appearance of the calculator and layout.
script.js: JavaScript that provides interactivity, handles calculations, keyboard support, and toggles the advanced layout.
How It Works
Basic Functions: The calculator allows you to perform simple arithmetic operations like addition, subtraction, multiplication, and division. These can be entered by clicking the buttons or by using the keyboard.

Advanced Functions:

The "More" button toggles visibility of the advanced functions (like percentage, factorial, e^x, and π).
You can also enter these advanced functions using the keyboard (e.g., p or P for π, e for e^x, etc.).
History: After each calculation, the result is saved to a history list below the calculator. You can see past calculations in this section.

Keyboard Support: All numbers, operators, and functions can be typed using the keyboard:

Numbers: 0-9
Basic operators: +, -, *, /
Special functions: %, !, e, p (for π), (, )
Backspace: Backspace key
Clear: C key
Perform calculation: Enter key
How to Use
Enter numbers by clicking on the respective buttons or typing directly from your keyboard.
Use the operators (+, -, *, /) to build your arithmetic expression.
Press Enter or click the = button to calculate the result.
You can also clear the input using the C button or Backspace key.
For advanced functions, click the "More" button or press the respective keys (e.g., p for π, e for e^x).
Customization
Feel free to modify the CSS file (style.css) to adjust the layout and appearance of the calculator. You can change the size of the buttons, colors, borders, or add any other custom styling as needed.

The JavaScript file (script.js) can be modified to add more advanced features or alter the existing functionality.

Known Issues
Eval Function: The current implementation uses the JavaScript eval() function to evaluate mathematical expressions. It is advised to use caution with eval() in production environments, as it can execute arbitrary code. In a more secure implementation, you might want to replace eval() with a safer math parser.
License
This project is open-source and free to use for personal or educational purposes. Feel free to contribute or suggest improvements.

