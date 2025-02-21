# JavaScript Loose Equality and NaN

This repository demonstrates a common JavaScript error related to loose equality (==) and the resulting NaN (Not a Number) value when dealing with null and undefined.

The `bug.js` file contains the erroneous code, while `bugSolution.js` shows the corrected version using strict equality (===).

## Problem

Loose equality in JavaScript can lead to unexpected behavior, especially when comparing null and undefined.  The loose equality operator (==) performs type coercion, which can result in unintended results.

## Solution

Using strict equality (===) prevents type coercion and ensures that the comparison is accurate. This avoids the unexpected NaN result in cases involving null or undefined.