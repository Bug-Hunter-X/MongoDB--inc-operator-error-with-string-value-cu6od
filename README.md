# MongoDB $inc operator error with string value

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a number.  The `$inc` operator is designed to increment a numerical field by a specified amount.  Attempting to increment with a string will cause an error.

## Bug
The `bug.js` file contains the erroneous code.  The error is caused by passing '1' (a string) as the increment value instead of 1 (a number).

## Solution
The `bugSolution.js` file provides the corrected code. The key change is using the numerical value `1` instead of the string `'1'` to correctly increment the counter.