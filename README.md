# MongoDB $inc operator error
This repository demonstrates an incorrect usage of the `$inc` operator in a MongoDB update query.  The error arises from using a string value instead of a numeric value for incrementing a field.

## Bug
The original code attempts to increment the `age` field by '1' (string), which is not a valid operation.  The correct usage requires using a numeric value (integer or float).

## Solution
The solution shows how to correctly use the `$inc` operator to increment the `age` field by 1 (integer).