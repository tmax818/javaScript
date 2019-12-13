

# Functions

- topic you must understand, central to JS.

-  two step process: define and run

-  action, chunk of code 

~~~js
"hello".toUpperCase()
=> "HELLO"
~~~

function statement

~~~js
function funcName(){
    //body
}
~~~

"Functions are the bread and butter of JavaScript programming." - eloquent

## Function Definition

"A function definition is a regular binding where the value of the binding is
a function." - el

~~~js
const square = function(x) {
return x * x;
};
console.log(square(12));
// → 144
~~~

"A return keyword without an expression after it will cause the function to return undefined. Functions that don’t have a return statement at all, such as makeNoise , similarly return undefined." - el

## Scope

"Each binding (variable) has a *scope*, which is the part of the program in which the binding is visible. For bindings defined outside of any function or block, the scope is
the whole program—you can refer to such bindings wherever you want. These
are called *global*."

## Vocabulary

parameter

body

return

caller

scope 

global

local

block

nested scope

lexical scoping

function declaration

arrow functions

the call stack

closure

recursion

side effects

