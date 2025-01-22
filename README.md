# CSS `calc()` Whitespace and Operator Precedence Errors

This repository demonstrates a common error encountered when using the CSS `calc()` function.  The problem arises from either incorrect whitespace placement around arithmetic operators or a misunderstanding of operator precedence.

**bug.css** showcases the erroneous code.  **bugSolution.css** provides the corrected version.

Understanding operator precedence in CSS `calc()` is crucial.  Multiplication and division are performed before addition and subtraction.  Always use parentheses to ensure the desired order of operations.

Ensure there's no extra space around the '+' and '-' operators. This can lead to calculation errors in various browsers.