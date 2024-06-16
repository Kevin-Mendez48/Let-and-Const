- What is the difference between var and let?
- What is the difference between var and const?
- What is the difference between let and const?
- What is hoisting?

The main difference between var and let is the scope. Var means the variable is accessible from the whole function. Whereas let makes the variable accessible only in the block. In essence, Var is a global variable, whereas let is a local. Var can be re-declared, wheras let cannot.

The difference between var and const is the same as the var and let. both can't be re-declared and are local variables.

The difference between let and const is while they cannot be re-declared, let allows re-assignment of the variable. Const is unable to be re-assigned.

Hoisting is when the variable is pulled to the top of the local / global scope during while the code is being compiled. This process happens before execution and let/const will yield the same error. "ReferenceError" happens when the code is pulled up during the compiling phase and the compiler will not allow the variables to initialize.
