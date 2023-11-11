# Calculator
Calculator application that parses text input as mathematical expression

## Details
As input the calculator accepts strings representing expressions with operations provided on a 4-function calculator: +,-,*,/,(,). 
Expressions are evaluated following PEMDAS rules, though exponential functionality is not implemented.

## Implementation
The application relies on an equation grammar that determines the order of operations.
After text parsing, the calculator uses built-in C++ operation to perform the actual calculation.
