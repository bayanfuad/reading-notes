# In memory storage 

## What is a ‘call’?
function invocation

## How many ‘calls’ can happen at once?
only 1 call can happen in an asynchronous programming

## What does LIFO mean?
Last In First Out

## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();

## What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

for more info check out this source Understanding the JavaScript Call Stack
## What is a ‘reference error’?
when you try to use a variable that is not yet declared, it is also a common thing when using const and let

## What is a ‘syntax error’?
this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

## What is a ‘range error’?
A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String

## What is a ‘type error’?
Like the name indicates, this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## What is a breakpoint?
In the debugger window, you can set breakpoints in the JavaScript code. At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

## What does the word ‘debugger’ do in your code?
it lets the code has more tools to watch and fetch data and variables during excution

## Things I want to know more about
stack overflow and error massages.
