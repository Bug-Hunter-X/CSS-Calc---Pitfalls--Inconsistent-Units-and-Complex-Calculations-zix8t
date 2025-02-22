# CSS Calc() Pitfalls: Inconsistent Units and Complex Calculations

This repository demonstrates common issues encountered when using the `calc()` function in CSS, specifically those related to inconsistent units and overly complex calculations.  The `bug.css` file showcases the problematic code, while `bugSolution.css` provides the corrected version and explanations.

**Issues:**
* Inconsistent units within a single `calc()` expression can produce unexpected results.
* Overly complex `calc()` expressions can be difficult to debug and maintain. 
* Using `calc()` with media queries might cause unexpected behavior if the calculations aren't carefully considered.

**Solutions:**
* Ensure consistent units are used within a single `calc()` expression.
* Break down complex calculations into smaller, more manageable steps.
* Carefully test your `calc()` expressions across different viewport sizes and devices.