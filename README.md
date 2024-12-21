# MongoDB $inc operator type error
This repo contains a demonstration of a common error when using the `$inc` operator in MongoDB update operations.  The error arises from providing a string value instead of a numeric value to the `$inc` operator.  The solution demonstrates how to correctly use the operator.

## Bug
The `bug.js` file shows an example of how the `$inc` operator is incorrectly used, providing a string value ('1'). This will lead to unexpected behavior rather than incrementing the counter.

## Solution
The `bugSolution.js` file presents the corrected version which provides the correct numeric value(1) to the `$inc` operator, ensuring proper increment behavior.
