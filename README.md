# Tailed vs Non-Tailed Recursion Workshop

## Introduction
This workshop is designed to help you understand the difference between tailed and non-tailed recursion. It is also designed to help you understand how to convert a non-tailed recursive function into a tailed recursive function.

## How to Solve the Workshop
1. Clone the repository
2. Run `npm install`
3. Run `npm test`
4. Open the `src/index.js` file
5. Read the instructions in the file
6. Write your code in the file
7. Run `npm test` to check your work
8. Repeat steps 5-7 until all tests pass


<hr>

Remainders:
## What is Tailed Recursion?
Tailed recursion is a recursive function where the recursive call is the last thing executed by the function. This means that the function does not need to do any more work after the recursive call returns. This allows the compiler to optimize the function by replacing the recursive call with a jump to the beginning of the function. This optimization is called tail call optimization.

## What is Non-Tailed Recursion?
Non-tailed recursion is a recursive function where the recursive call is not the last thing executed by the function. This means that the function needs to do more work after the recursive call returns. This prevents the compiler from optimizing the function by replacing the recursive call with a jump to the beginning of the function.