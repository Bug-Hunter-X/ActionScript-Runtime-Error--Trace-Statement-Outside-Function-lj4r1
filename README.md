# ActionScript Runtime Error: Trace Statement Outside Function

This repository demonstrates a common runtime error in ActionScript caused by placing a `trace` statement outside of a function.  The error occurs because ActionScript requires statements to be within a function's scope to be executed. 

## Bug Description
The original code attempts to use `trace` outside a function, resulting in a runtime error. The `trace` statement is not executed. 

## Solution
The solution involves encapsulating the `trace` statement within a function and then calling that function.