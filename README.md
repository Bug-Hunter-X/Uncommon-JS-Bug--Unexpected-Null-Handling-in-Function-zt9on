# Uncommon JavaScript Bug: Unexpected Null Handling

This repository demonstrates an uncommon bug in JavaScript related to unexpected null handling within a function. The function `foo` is designed to add two numbers, but its handling of null values leads to unexpected behavior.

## Bug Description

The `foo` function attempts to handle null values, but it does so incompletely and in a non-obvious way.  If either input is null, the function returns null. This works as expected in many cases, but if the code were reordered it would create inconsistent behavior.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js`.
3. Run the JavaScript code using a Node.js environment (or your preferred JavaScript environment). Note the unexpected behavior when the code is reordered.

## Solution

The `bugSolution.js` file provides a corrected version of the function. 

## Additional Notes

This bug highlights the importance of thorough null checking and consistent handling of edge cases when writing JavaScript functions.