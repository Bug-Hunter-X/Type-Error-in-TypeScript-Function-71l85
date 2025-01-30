# Type Error in TypeScript Function

This repository demonstrates a common type error in TypeScript where a function expects a certain type of argument, but a different type is provided.  The `bug.ts` file contains the buggy code, and `bugSolution.ts` provides a solution.

The error arises because the `add` function is explicitly typed to accept only numbers, yet we're passing a string. TypeScript's type system catches this error during compilation.

**How to run:**
1. Clone this repository.
2. Compile the code using a TypeScript compiler (e.g., `tsc bug.ts`).
3. Observe the compiler error message indicating the type mismatch.