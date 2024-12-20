# TypeScript Type Error: String Passed to Number Parameter

This repository demonstrates a common type error in TypeScript and how to solve it.  The error occurs when a string is passed as an argument to a function that expects a number.

## Bug

The `bug.ts` file contains a function `add` that takes two numbers as input and returns their sum.  However, the code attempts to pass a string as one of the arguments, resulting in a type error.

## Solution

The `bugSolution.ts` file provides a solution by using type guards to ensure both arguments are numbers before performing the addition. Alternatively, robust input validation or error handling is shown.