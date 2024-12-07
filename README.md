# MongoDB $inc Operator Error
This example demonstrates an error that can occur when using the `$inc` operator in MongoDB update operations. The `$inc` operator is designed to increment or decrement a numeric field by a specific value. However, providing a non-numeric value (e.g., a string) will result in an error. This repository provides a demonstration of the error and its solution.

## Bug
The bug lies in the incorrect usage of the `$inc` operator.  A string value is supplied as the increment, rather than a number. This causes MongoDB to reject the update operation.

## Solution
The solution involves correcting the value passed to the `$inc` operator to a valid number.