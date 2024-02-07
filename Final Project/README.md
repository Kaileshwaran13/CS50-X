# Basic Calculator in C

This is a simple console-based calculator program implemented in C, allowing users to perform basic arithmetic operations. The calculator supports addition, subtraction, multiplication, and division.

## Getting Started

To run the calculator, follow the steps below:

1. Make sure you have a C compiler installed on your system.
2. Copy the C code provided into a new file, for example, `calculator.c`.
3. Open a terminal or command prompt and navigate to the directory containing the file.
4. Compile the code using the following command:

    ```bash
    gcc calculator.c -o calculator
    ```

5. Run the compiled executable:

    ```bash
    ./calculator
    ```

## Code Overview

The calculator program consists of several functions for performing arithmetic operations and a main function to interact with the user.

### Arithmetic Functions

1. **addDigits(int num1, int num2):**
   - Adds two integer numbers and returns the result.

2. **subDigits(int num1, int num2):**
   - Subtracts the second integer from the first and returns the result.

3. **mulDigits(int num1, int num2):**
   - Multiplies two integer numbers and returns the product.

4. **divDigits(int num1, int num2):**
   - Divides the first integer by the second and returns the quotient.

### Main Function

The `main` function prompts the user to input two numbers and an operator. It then calculates the result using a switch statement based on the chosen operator.

## Example

Let's say you want to add two numbers, 5 and 3. To do this, follow these steps:

1. Run the compiled executable (`./calculator`).
2. Enter the first number when prompted: `Num1 = 5`
3. Enter the second number when prompted: `Num2 = 3`
4. Enter the operator for addition: `Operator = +`
5. The program will display the equation: `Given Equation: 5 + 3`
6. The result will be shown: `Answer of "5 + 3 = 8"`
