🧮 Custom Calculator with Exception Handling in Java

This project is a custom calculator built in Java that demonstrates the use of user-defined exceptions along with basic arithmetic operations.

✨ Features

Supports Addition (+), Subtraction (-), Multiplication (*), and Division (/).

Custom exceptions to handle invalid or restricted inputs:

InvalidInputException → Triggered when an unsupported operator is entered.

CannotDivideBy0Exception → Prevents division by zero.

MaxInputException → Restricts inputs larger than 100000.

MaxMultiplierReachedException → Prevents multiplication if inputs exceed 7000.

Provides user-friendly error messages for better clarity.

🛠 How It Works

The user is prompted to enter two numbers.

The user selects the operation (+, -, *, /).

The calculator checks inputs and applies custom exception handling if rules are violated.

The result (or exception message) is displayed to the user.
