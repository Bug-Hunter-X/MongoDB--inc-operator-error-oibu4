# MongoDB $inc operator error

This repository contains a demonstration of an incorrect usage of the MongoDB $inc operator and its solution.

The bug occurs when attempting to increment a field using a string value instead of a number with the `$inc` operator in MongoDB update operation.

## Bug
The `bug.js` file demonstrates the incorrect usage of the `$inc` operator.  It attempts to increment a field with a string value, resulting in an error.  This results in an error because `$inc` expects a numerical value.

## Solution
The `bugSolution.js` file provides the correct way to increment a field using the `$inc` operator with a numeric value. This demonstrates the correct usage of the `$inc` operator, ensuring that the field is incremented correctly.