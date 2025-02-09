# JavaScript Loose Equality Bug: Handling Null and Undefined

This repository demonstrates a common JavaScript bug involving loose equality (`==`) and the handling of `null` and `undefined` values.  The `foo` function intends to return 0 when `x` is `null`, but unexpectedly returns `NaN` when `x` is `undefined` due to loose equality's behavior.

The solution showcases the importance of using strict equality (`===`) for accurate comparisons, ensuring the function behaves consistently for both `null` and `undefined`.

## Bug:

The `bug.js` file contains the buggy function using loose equality. 

## Solution:

The `bugSolution.js` file demonstrates the corrected function using strict equality for reliable comparison of `null` and `undefined`.