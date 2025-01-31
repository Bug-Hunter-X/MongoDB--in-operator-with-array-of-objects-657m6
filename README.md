# MongoDB $in Operator with Array of Objects
This repository demonstrates a common error when using the `$in` operator in MongoDB queries with an array of objects.  The incorrect usage and the corrected solution are provided.

## Problem
The `$in` operator is typically used to check if a field's value exists within a specified array of values. However, when attempting to use it with an array of objects, it might not produce the expected results.

## Solution
To correctly filter based on the values within objects in an array, you should use the `$elemMatch` operator.

## How to Run
1.  Make sure you have MongoDB and Node.js installed.
2.  Clone this repository.
3.  Run `npm install` to install required packages.
4.  Run the `bug.js` and then `bugSolution.js` to see the difference in output. 