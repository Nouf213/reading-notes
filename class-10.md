# JavaScript Debugging

## Code Debugging

Programming code might contain syntax errors, or logical errors. (Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors).

Searching for (and fixing) errors in programming code is called code debugging.
JavaScript Debuggers
Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

Built-in debuggers can be turned on and off, forcing errors to be reported to the user. _____

console.log() Method
If your browser supports debugging, you can use

console.log()

to display JavaScript values in the debugger window

Setting Breakpoints
In the debugger window, you can set breakpoints in the JavaScript code.

At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

After examining values, you can resume the execution of code (typically with a play button).

The debugger Keyword
The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.

This has the same function as setting a breakpoint in the debugger.

If no debugging is available, the debugger statement has no effect.

## Note :

Debugging is the process of testing, finding, and reducing bugs (errors) in computer programs. The first known computer bug was a real bug (an insect) stuck in the electronics. _______

JavaScript Errors - Throw and Try to Catch
The try statement lets you test a block of code for errors.

The catch statement lets you handle the error.

The throw statement lets you create custom errors.

The finally statement lets you execute code, after try and catch, regardless of the result. ___

JavaScript try and catch

1. The try statement allows you to define a block of code to be tested for errors while it is being executed.

2. The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

The JavaScript statements try and catch come in pairs:

try {
  Block of code to try
}
catch(err) {
  Block of code to handle errors
}
The throw Statement
The throw statement allows you to create a custom error.

Technically you can throw an exception (throw an error).

The exception can be a JavaScript String, a Number, a Boolean or an Object:

throw "Too big";    // throw a text
throw 500;          // throw a number
Error Name Values
Six different values can be returned by the error name property:

* Error Name Description
* EvalError An error has occurred in the eval() function
* RangeError A number “out of range” has occurred
* ReferenceError An illegal reference has occurred
* SyntaxError A syntax error has occurred
* TypeError A type error has occurred
* URIError An error in encodeURI() has occurred
