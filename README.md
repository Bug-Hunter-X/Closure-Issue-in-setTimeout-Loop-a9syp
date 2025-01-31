# Closure Issue in setTimeout Loop

This example demonstrates a common closure issue in JavaScript when using `setTimeout` within a loop.  The expected behavior is to print numbers 0 through 9, but the actual output will be 10 ten times due to how closures work with the loop variable.