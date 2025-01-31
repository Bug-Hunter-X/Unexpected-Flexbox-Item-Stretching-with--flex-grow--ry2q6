# Unexpected Flexbox Item Stretching

This repository demonstrates an uncommon CSS flexbox layout issue.  Even-numbered items unexpectedly stretch to fill the available space, despite only `flex-grow` being modified.  The bug is caused by the interaction between `flex-grow`, `align-items: center`, and `justify-content: center`.  The solution provides a workaround to prevent this issue.

## Bug
The `bug.css` file contains the CSS code exhibiting the problem.  Observe how the red boxes (even numbered items) stretch unexpectedly.

## Solution
The `bugSolution.css` demonstrates a solution, which includes adding explicit widths to the items, eliminating the unexpected stretching issue.