## In Memory Storage

1. A 'call' refers to the execution of a function in programming. When a function is called, the program temporarily suspends the execution of the current code and jumps to the function's code to execute it.

2. The number of calls that can happen at once depends on the resources available in the system. Generally, modern computer systems can handle multiple calls at the same time.

3. LIFO stands for Last In, First Out. It is a method of organizing and manipulating data in which the last item to be added to a list or stack is the first one to be removed. In programming, the call stack is typically organized using the LIFO principle.

4. A call stack is a data structure used by computer programs to manage function calls. It keeps track of the functions that are currently being executed, and the order in which they were called.
function a() {
  b();
}

function b() {
  c();
}

function c() {
  console.log('Hello, world!');
}

a();


5. A Stack Overflow occurs when the call stack exceeds its maximum size. This can happen when a program is stuck in an infinite loop or when too many function calls are made without returning.

6. JavaScript error messages:

A 'ReferenceError' occurs when a variable is used but not defined.
A 'SyntaxError' occurs when there is a problem with the syntax of the code.
A 'RangeError' occurs when a number is outside the range of allowed values.
A 'TypeError' occurs when a value is not of the expected type.

7. A breakpoint is a point in the code where the program will pause execution so that the developer can inspect the state of the program.

8. A debugger is a tool that allows developers to identify and fix errors in their code. It allows developers to step through code, set breakpoints, and inspect the state of the program at different points in its execution.

## Things I would like to know more about