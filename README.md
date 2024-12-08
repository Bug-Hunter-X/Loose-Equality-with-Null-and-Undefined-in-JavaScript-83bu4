# Loose Equality with Null and Undefined in JavaScript

This repository demonstrates a common JavaScript error related to loose equality (==) when comparing null and undefined.  The `bug.js` file showcases the problem, while `bugSolution.js` provides the corrected code using strict equality (===).

## Problem

JavaScript's loose equality operator (==) performs type coercion before comparison. This can lead to unexpected behavior when comparing null and undefined to other values, including 0 and NaN.

## Solution

The solution involves using strict equality (===), which doesn't perform type coercion. This ensures accurate comparison without unexpected results.