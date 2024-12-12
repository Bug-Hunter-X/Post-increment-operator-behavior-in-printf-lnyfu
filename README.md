# Post-increment Operator in C
This example demonstrates a common misunderstanding of the post-increment operator (`x++`) in C when used within the `printf` function. The output may be unexpected for those unfamiliar with the order of evaluation.

## Bug
The code intends to print the value of `x` (10), then increment `x` and print the incremented value (11). However, the actual output is different.

## Solution
The solution involves a better understanding of how the post-increment operator functions.  The post-increment operator increments the variable *after* its value has been used in the expression.  Therefore, changes to the code need to be made to achieve the intended behavior.  It's crucial to correctly utilize the post-increment operator to avoid producing unwanted results.
