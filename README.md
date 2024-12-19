# CSS calc() Inconsistency with Mixed Units

This repository demonstrates an uncommon bug related to the CSS `calc()` function when using a mix of percentage and pixel units.  The issue arises when the parent container's width is dynamic, leading to inaccurate calculations.

The `bug.css` file contains the problematic CSS. The `bugSolution.css` demonstrates a solution that provides more reliable behavior across different browsers and parent container sizes.