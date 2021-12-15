
JavaScript interview questions <br>
1."use strict"
"use strict" is to indicate that the code should be executed in "strict mode". 
For example: 
Undeclared variables are not allowed 
Deleting a function is not allowed (function x(a, b); delete x)
Duplicating a parameter name is not allowed: function a(item, item)
Octal numeric literals are not allowed: let a = 010;
Octal escape characters are not allowed: let a = /010
The this keyword in functions behaves differently in strict mode.The this keyword refers to the object that called the function. If the object is not specified, functions in strict mode will return undefined and functions in normal mode will return the global object (window):

2.“THIS” keyword in JavaScript
this keyword refers to the object it belongs to. 

It has different values depending on where it is used:
In a method, this refers to the owner object.
Alone, this refers to the global object.
In a function, this refers to the global object.
In a function, in strict mode, this is undefined.
In an event, this refers to the element that received the event.
Methods like call(), and apply() can refer this to any object.

3.JavaScript Scope
Scope determines the accessibility (visibility) of variables.
JavaScript has 3 types of scope:
Block scope - Variables declared inside a { } block cannot be accessed from outside the block
Function scope - Variables declared within a JavaScript function, become LOCAL to the function.
Global scope - Variables declared Globally (outside any function) have Global Scope

4.Data types
They are two:  primitive values and reference type(objects).
Primitives: Boolean, Number, String, Null, Undefined, Symbol
Reference: Objects, Arrays, Functions
