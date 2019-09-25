## Debugging Homework

###### 1. What is the purpose of a breakpoint?

A breakpoint is a source code marker that allows you to suspend a running program at a certain point so you can examine its behaviour.

The application will run as normal until it hits the line with the breakpoint. It will then pause the application and launch the debugger console.

###### 2. Does the line of code on a breakpoint run when you start debugging?

It doesn't. The program will run until it reaches the breakpoint.

The line highlighted in blue indicates where the debugger currently is. i.e - what line is waiting to be run.

###### 3. How do we debug the next line of code?

Use Step over button. This allows us to move to the next line.

If something is wrong, the line will not be run and this allows us to see that something needs to be fixed.

###### 4. What does the step into command do?

Switch to highlighted method and pause at the top of that method.

###### 5. What is the difference between evaluate expression and evaluate code fragment?

 Evaluate expression:- You can only evaluate one expression. Evaluate java code on instances of objects we have created. Don't need to use semi-colons.

 Evaluate code fragment:- You can run multiple methods on multiple lines of code and create variables. Need to use semi-colons so like normal Java.
