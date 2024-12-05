# TypeScript Type Error Bug
This repository demonstrates a common TypeScript error related to type mismatches in function arguments.  The `bug.ts` file contains the erroneous code, while `bugSolution.ts` provides a corrected version.

The bug arises from passing a string argument to a function that expects a number. TypeScript's type system catches this error during compilation, preventing runtime surprises.

## How to Reproduce
1. Clone this repository.
2. Open `bug.ts` and observe the type error. 
3. Compile the code using the TypeScript compiler (tsc). You will see a compilation error.
4. Examine `bugSolution.ts` to see how to correct the error.

## Learning Points
This example highlights the importance of TypeScript's static typing. By defining the types of function parameters, we can catch type-related errors at compile time, leading to more robust and maintainable code.