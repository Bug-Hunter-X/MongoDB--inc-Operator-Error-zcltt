# MongoDB $inc Operator Error

This repository demonstrates an example of an uncommon error in MongoDB related to the `$inc` operator.

The `$inc` operator is used to increment a numerical field in a document. A common mistake is to provide a string value instead of a number to the `$inc` operator. This leads to unexpected results, potentially no changes, or errors.

## Bug
The provided `bug.js` file shows how using a string with the `$inc` operator causes the update to fail or have unexpected behavior.

## Solution
The `bugSolution.js` file presents the correct solution by providing a numerical value to the `$inc` operator, ensuring the operation performs as expected.

This example highlights the importance of data type validation in MongoDB operations to prevent unexpected and subtle errors.