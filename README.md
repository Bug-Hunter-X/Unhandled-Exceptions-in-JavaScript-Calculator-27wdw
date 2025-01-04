# Unhandled Exceptions in JavaScript Calculator

This repository demonstrates a common error in JavaScript: unhandled exceptions. The `operate` function throws errors for division by zero and invalid operators, but the calling code doesn't handle these exceptions, leading to program crashes.  This example highlights the importance of robust error handling in JavaScript applications.

## Bug

The `bug.js` file contains the buggy code.  The `operate` function throws errors if you try to divide by zero or use an invalid operator. However, these errors are not caught, causing the program to terminate unexpectedly.

## Solution

The `bugSolution.js` file provides a corrected version of the code. It uses a `try...catch` block to handle the potential `Error` objects thrown by the `operate` function. This prevents the program from crashing and allows for more graceful error handling. 