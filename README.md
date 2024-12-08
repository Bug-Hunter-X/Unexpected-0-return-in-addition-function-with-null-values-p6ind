# JavaScript Bug: Unexpected 0 Return in Addition Function

This repository demonstrates a common yet subtle bug in JavaScript involving null value handling in arithmetic operations.

## Bug Description

The `foo` function is designed to add two numbers. However, it unexpectedly returns 0 if either of the inputs is `null`.

## Bug Reproduction

1. Clone the repository.
2. Open `bug.js` and examine the code.
3. Run the file using a JavaScript runtime (Node.js, for example).
4. Observe that the function returns 0 when one of the inputs is `null`, even though a more intuitive behavior might be to return the other number or throw an error.

## Solution

The `bugSolution.js` file offers a corrected version of the function, showcasing improved null value handling.

## Additional Notes

This highlights the importance of thorough null checking and robust error handling in JavaScript to prevent unexpected behavior and maintain code reliability.