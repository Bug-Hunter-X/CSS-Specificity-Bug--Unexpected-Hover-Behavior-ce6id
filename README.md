# CSS Specificity Bug: Unexpected Hover Behavior

This repository demonstrates an uncommon CSS bug related to selector specificity. When using both classes and pseudo-classes (like :hover), the order of specificity can lead to unexpected results. The bug.css file showcases the problem, while bugSolution.css presents a solution.

**Problem:** The intended behavior is to have a yellow background on hover for elements with the 'highlight' class. However, due to specificity, the general :hover style on 'div' overrides it.

**Solution:** The solution modifies the specificity to ensure the '.highlight:hover' rule takes precedence.