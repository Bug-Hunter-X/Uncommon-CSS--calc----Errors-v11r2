# Uncommon CSS `calc()` Errors

This repository demonstrates some uncommon errors that can occur when using the CSS `calc()` function.  These errors often involve unit mismatches, incorrect operator precedence, and missing spaces around operators.

The `bug.css` file contains examples of these errors, while `bugSolution.css` provides the corrected code.

**Common Errors:**

* **Unit Mismatch:**  Mixing units without proper conversion (e.g., `calc(100px + 5em)` without converting em to px). 
* **Operator Precedence:** Incorrect order of operations due to missing parentheses.
* **Missing Spaces:** Forgetting spaces around operators (e.g., `calc(100%-5px)`).