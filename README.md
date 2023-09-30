# TASK 2: Design a simple calculator with basic arithmetic operations.
Prompt the user to input two numbers and an operation choice.

Perform the calculation and display the result.
--------------------------------------------------------------------------------------


 Here's a detailed explanation of the steps involved in creating a simple calculator using Python:

1. **Function Definitions**:
    - We begin by defining four functions: `add`, `subtract`, `multiply`, and `divide`. Each of these functions takes two arguments (two numbers) and returns the result of the corresponding arithmetic operation.

2. **Main Calculator Function** (`calculator`):
    - We define a main function called `calculator` to handle the user interaction and calculations.

3. **Display Options**:
    - Inside the `calculator` function, we first display the available options to the user. These options represent the four basic arithmetic operations: addition, subtraction, multiplication, and division.

4. **User Input for Operation**:
    - We use the `input` function to prompt the user to enter their choice of operation. The user should type one of the operation names ('add', 'subtract', 'multiply', or 'divide').

5. **Input Validation**:
    - We check if the user's input is a valid operation by using a conditional statement (`if operation not in ('add', 'subtract', 'multiply', 'divide'):`). If the input is not valid, we display an error message and return from the function.

6. **User Input for Numbers**:
    - Next, we prompt the user to enter two numbers, one at a time, using the `input` function. We convert the input to floating-point numbers using `float()` to allow for decimal inputs.

7. **Perform Calculation**:
    - Depending on the user's chosen operation, we call the corresponding function (`add`, `subtract`, `multiply`, or `divide`) with the two input numbers. This calculates the result of the chosen operation.

8. **Display Result**:
    - Finally, we display the result of the calculation using the `print` function. The result is stored in the `result` variable, which is determined by the chosen operation.

9. **Calling the Calculator Function**:
    - After defining the `calculator` function, we call it at the end of the script to start the calculator program. This allows the user to input their choices and perform calculations.




