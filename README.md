# Day 10: Calculator Project

We created a simple calculator program. This calculator can perform basic arithmetic operations like addition, subtraction, multiplication, and division, allowing users to continue calculations with the current result or start fresh.

## What We Learned

- Defining **functions with return values** to perform operations.
- Using a **dictionary to map operation symbols to functions** for clean code.
- Handling **multiple return values** and passing data between functions.
- Writing **docstrings** (though optional here) to explain what functions do.
- Managing program flow with **loops and recursion** to allow continuous calculations.

## How the Code Works

- The program defines separate functions for each arithmetic operation.
- It stores these functions in a dictionary with operation symbols as keys.
- The calculator function:
  - Prompts the user for the first number.
  - Displays available operations.
  - Takes the user’s operation choice and the next number.
  - Calculates and displays the result.
  - Asks if the user wants to continue with the current result or start over.
- If continuing, the result becomes the new first number.
- If starting over, the program clears the screen and restarts the calculator.

