# Type 'string[]' is not assignable to type 'string'
This TypeScript bug demonstrates a common type error: assigning an array of strings to a variable expecting a single string.

## Bug
The `greeter` function expects a single string as input but receives an array of strings (`string[]`).

## Solution
The solution involves either modifying the `greeter` function to handle string arrays or changing how the `user` variable is defined.