# JavaScript: Unexpected Null Handling in Addition Function

This repository demonstrates a common yet subtle bug in JavaScript related to handling null values in a function.  The `foo` function is designed to add two numbers but unexpectedly returns 0 if either input is null.  This behavior might not be the intended behavior if you want null values to be treated as 0 for addition purposes.

The `bug.js` file contains the buggy code, and `bugSolution.js` shows how to correct this issue.  The bug is described in more detail in the `bugDescription` section. 