# Basic Arithmetic Calculator in C

This is a simple command-line calculator written in C that supports basic arithmetic operations, including addition, subtraction, multiplication, division, and exponentiation. The calculator validates input to prevent invalid expressions and handles sequential calculations using previous results (`Ans` feature).  

## Features
- Supports operators: `+`, `-`, `*`, `/`, and `^` (exponentiation).
- Prevents invalid expressions through input validation.
- Handles division by zero errors.
- Allows for continuous calculations using the result from previous operations.

## Upcoming Features
I plan to add the following features:
- **Handling Negative Numbers**: Allow negative numbers in input.
- **Operator Precedence**: Perform operations with correct precedence (e.g., `*` and `/` before `+` and `-`).
- **Floating Point Numbers**: Support decimal numbers in calculations.
*Feel free to open an issue if you'd like to contribute or suggest improvements.*

## Example
```bash
   4 + 65 - 9
   = 60
   Ans / 10 * 3
   = 18
