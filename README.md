# Unexpected Behavior with Null Values in foo Function

This repository demonstrates a common JavaScript error involving unexpected behavior when null values are passed to a function.

## Bug Description
The `foo` function does not explicitly handle `null` values passed as arguments. When `null` values are passed, the function silently returns without throwing an error or providing any feedback. This can lead to unexpected behavior and make debugging difficult.

## Solution
The solution explicitly checks for `null` values and handles them appropriately.  This could involve throwing an error, returning a default value, or performing alternative logic.

## How to reproduce
1. Clone the repository.
2. Run `bug.js`  with different values for a and b including `null`. Observe the behavior. 
3. Run `bugSolution.js` and observe the improved error handling.
