# Inconsistent width calculations using calc() in CSS
This repository demonstrates a common issue encountered when using the `calc()` function in CSS to calculate widths dynamically.  Some browsers might misinterpret the units if the parent element doesn't have a specified width, leading to incorrect layout.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` file offers a solution to mitigate this issue.

**Issue:**
Inconsistent width calculation using `calc(100% - 20px)` when the parent element doesn't have an explicit width.

**Solution:**
Ensure the parent element has a defined width, or use alternative layout techniques like flexbox or grid to achieve the desired result.