# TypeScript: Handling undefined in function parameters

This repository demonstrates a common TypeScript error where a function's parameter type only considers `null`, not `undefined`.  The `bug.ts` file showcases this error, while `bugSolution.ts` provides the corrected code.

## The Problem
The original code only handles `null` values, which leads to a type error when an `undefined` value is passed.  This is because `undefined` is a distinct type from `null` in TypeScript.

## The Solution
The solution is to modify the function's parameter type to include `undefined`. This allows the function to accept both `null` and `undefined` values gracefully.