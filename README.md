# Unexpected Null Return with Strict Equality in JavaScript

This repository demonstrates a common error in JavaScript where using the strict equality operator (===) with null values can lead to unexpected behavior. The code in 'bug.js' shows a function that returns null if either input is null, even if the other input is a valid number.  The 'bugSolution.js' file provides a corrected version.

## Bug Description:
The `foo` function is designed to add two numbers. However, its use of strict equality (`===`) with `null` causes it to prematurely return `null` if either input is `null`, ignoring the other input value.

## Solution:
The solution involves checking for null values separately and handling them appropriately (e.g., returning 0 if either input is null).

## How to run the code:
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in a JavaScript environment (e.g., a browser's developer console, Node.js).
3. Run the code to observe the difference in behavior between the buggy and corrected versions.
