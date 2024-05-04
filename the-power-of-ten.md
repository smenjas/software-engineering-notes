# [The Power of Ten](https://en.wikipedia.org/wiki/The_Power_of_10:_Rules_for_Developing_Safety-Critical_Code)

1. Simple Control Flow: no goto, setjump, longjump, or recursion.
2. Limit all loops, by an integer number of iterations.
3. Don't use the heap (no malloc or free), only the stack.
4. Limit function size to do one thing, no longer than 60 lines.
5. Use at least two runtime assertions per function.
6. Practice data hiding: declare variables at the lowest scope.
7. Check return values *always*, or cast to void if you must.
8. Limit the preprocessor: e.g. don't conditionally compile code.
9. Restrict pointer use, only dereference one level, no function pointers.
10. Be pedantic: compile with all warnings enabled.
