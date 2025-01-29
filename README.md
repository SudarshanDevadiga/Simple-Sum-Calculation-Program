# Simple Sum Calculation Program

A basic C++ program that calculates and displays the sum of two predefined integers.

## Description

This program demonstrates simple arithmetic operations in C++. It initializes two integer variables, calculates their sum, and outputs the result to the console.

### Key Features
- Variable declaration and initialization
- Basic arithmetic operation (addition)
- Console output using `std::cout`

## Code Structure

```cpp
#include <iostream>

int main() {
    // Declare variables to store the two numbers
    int num1 = 5;
    int num2 = 10;

    // Calculate the sum of the two numbers
    int sum = num1 + num2;

    // Display the result
    std::cout << "The sum of " << num1 << " and " << num2 << " is: " << sum << std::endl;
    
    // Return 0 to indicate successful program execution 
    return 0;
}
