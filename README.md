# Python Calculator
Step 1 — Prompt users for input
Calculators work best when a human provides equations for the computer to solve. We’ll start writing our program at the point where the human enters the numbers that they would like the computer to work with.
we’ll use Python’s built-in input() function that accepts user-generated input from the keyboard. Inside of the parentheses of the input() function we can pass a string to prompt the user. We’ll assign the user’s input to a variable.

Step 2 — Adding operators
Before our program is complete, we’ll add a total of 4 mathematical operators: + for addition, - for subtraction, * for multiplication, and / for division.

Step 3 — Adding conditional statements
With our calculator.py program, we want the user to be able to choose among the different operators. So, let’s start by adding some information at the top of the program, along with a choice to make, so that the person knows what to do.

Step 4 — Defining functions
To handle the ability to perform the program as many times as the user wants, we’ll define some functions. Let’s first put our existing code block into a function. We’ll name the function calculate() and add an additional layer of indentation within the function itself. To ensure the program runs, we’ll also call the function at the bottom of our file
