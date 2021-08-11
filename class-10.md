# JS Debugging

JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

+ **EXECUTION CONTEXT** every statement in a script lives in one of three execution contexts.

+ **VARIABLE SCOPE** the first two execution contexts correspond with the notion of scope.

**UNDERSTANDING SCOPE**
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

**Error objects** can help you find where your mistakes are
and browsers have tools to help you read them.

## HOW TO DEAL WITH ERRORS

+ DEBUG THE SCRIPT TO FIX ERRORS
+ HANDLE ERRORS GRACEFULLY

The console will show you when there is an error in your JavaScript. It also displays the line where it became a problem for the interpreter.

JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.

If you know that you may get an error, you can handle
it gracefully using the try, catch, finally statements.
Use them to give your users helpful feedback.

