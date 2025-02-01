# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB's `updateOne` method.  The error arises from providing a string value instead of a numeric value to the `$inc` operator, which leads to unexpected behavior or errors. The solution demonstrates the correct usage with a numeric value.

## Bug
The `bug.js` file contains the incorrect implementation: attempting to increment the `counter` field with a string value ('1'). This will likely throw an error or produce unexpected results.

## Solution
The `bugSolution.js` file demonstrates the corrected implementation. It uses a numeric value (1) for incrementing the `counter` field. This ensures the `$inc` operator functions correctly and increments the counter as intended.