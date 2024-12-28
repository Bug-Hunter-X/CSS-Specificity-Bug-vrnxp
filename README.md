# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity. The `bug.css` file contains CSS code that exhibits the unexpected behavior, while `bugSolution.css` provides a solution.

## Bug Description
A more specific selector unintentionally overrides styling applied by a less specific selector.

## Solution
The solution addresses the specificity issue by adjusting selectors to ensure the desired styling is applied correctly.  This often involves rethinking the class structure or using the `!important` flag (sparingly).