# Unexpected Width Calculation with calc() in CSS

This repository demonstrates an uncommon bug related to the `calc()` function in CSS.  In certain situations, calculating the width of an element using `calc()` can lead to unexpected and incorrect results. This is particularly true when the parent element's width is not explicitly defined or is impacted by other CSS properties like padding, margin, or border.

The `bug.css` file contains the problematic CSS rule.  The `bugSolution.css` file provides a solution to fix this issue.

**Bug:** The `calc(100% - 10px)` calculation might not work as expected if the parent element doesn't have a defined width or if its width is dynamically adjusted by other styles.

**Solution:**  Explicitly set the width of the parent element or consider using alternative approaches to achieve the desired layout.