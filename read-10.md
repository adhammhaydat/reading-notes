# In memory storage

### What is a ‘call’?

The call() method is a predefined JavaScript method. It can be used to invoke (call) a method with an owner object as an argument (parameter). With call() , an object can use a method belonging to another object.

### How many ‘calls’ can happen at once?
JavaScript is the single-threaded programming language. The JavaScript engine has only one call stack so that it only can do one thing at a time. When executing a script, the JavaScript engine executes code from top to bottom, line by line. In other words, it is synchronous

### What does LIFO mean?
Last In, First Out

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![](https://i.stack.imgur.com/uiCRx.png)

### What causes a Stack Overflow?
The most-common cause of stack overflow is excessively deep or infinite recursion, in which a function calls itself so many times that the space needed to store the variables and information associated with each call is more than can fit on the stack.

----------------------------------------------------

### What is a ‘refrence error’?
The ReferenceError object represents an error when a non-existent variable is referenced

### What is a ‘syntax error’?
The SyntaxError object represents an error when trying to interpret syntactically invalid code. It is thrown when the JavaScript engine encounters tokens or token order that does not conform to the syntax of the language when parsing code.

### What is a ‘range error’?

A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String.

### What is a ‘tyep error’?

The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type. A TypeError may be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function; 

### What is a breakpoint?

The Debugger Statements JavaScript Breakpoint will pause JavaScript execution whenever any debugger statement is executed if it's enabled. The All Exceptions JavaScript Breakpoint will pause JavaScript execution whenever any exception is thrown if it's enabled

### What does the word ‘debugger’ do in your code?

The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function. This has the same function as setting a breakpoint in the debugger. ... With the debugger turned on, this code will stop executing before it executes the third line.
