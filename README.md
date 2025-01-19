# Simple Calculator Project  

This is a C-based command-line calculator application that supports basic arithmetic operations, factorial calculation, and power computation. The program is designed to provide an interactive user experience with a menu-driven interface.  

## Features  

- **Addition**: Add two numbers.  
- **Subtraction**: Subtract one number from another.  
- **Multiplication**: Multiply two numbers.  
- **Division**: Divide one number by another with precision.  
- **Modulus**: Compute the remainder of a division operation (for integers).  
- **Power**: Calculate the power of a number (base^exponent).  
- **Factorial**: Compute the factorial of an integer.  
- **Interactive Menu**: A user-friendly menu guiding the operations.  

## Usage  

1. Run the program.  
2. Follow the on-screen instructions to select the desired operation.  
3. Input the required values as prompted.  
4. View the result of the operation.  

## Function Descriptions  

### Function Prototypes  
- `void addition();`: Performs addition of two numbers.  
- `void subtraction();`: Performs subtraction of two numbers.  
- `void multiplication();`: Performs multiplication of two numbers.  
- `void division();`: Performs division of two numbers.  
- `void modulus();`: Computes the remainder of integer division.  
- `void power();`: Calculates the power of a number.  
- `int factorial();`: Returns the factorial of an integer.  
- `void calculator_operations();`: Displays the menu of operations.  

### Main Function  
The `main()` function initializes the calculator program and provides an interactive menu for the user to select operations.  

## Requirements  

- **C Compiler**: GCC or equivalent.  
- **Header Files**:  
  - `<stdio.h>`: For standard input/output operations.  
  - `<conio.h>`: For console I/O functions (specific to certain compilers like Turbo C).  
  - `<math.h>`: For mathematical operations like power.  
  - `<stdlib.h>`: For general utility functions.  

## How to Compile and Run  

1. Copy the source code into a `.c` file (e.g., `calculator.c`).  
2. Open a terminal or command prompt.  
3. Compile the program:  
   ```bash
   gcc calculator.c -o calculator -lm
