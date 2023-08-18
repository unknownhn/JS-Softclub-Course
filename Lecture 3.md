# Recursion
Working of recursion in JavaScript A recursive function 
must have a condition to stop calling itself. Otherwise, the function is called indefinitely. Once the condition is met, the function stops calling itself. This is called a base condition.
# Can a recursive function call itself in javascript?
The Identifier in a FunctionExpression can be referenced from inside the FunctionExpression's FunctionBody to allow the function to call itself recursively. However, unlike in a FunctionDeclaration, the Identifier
in a FunctionExpression cannot be referenced from and does not affect the scope enclosing the FunctionExpression.
# Closure
A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function. 
In JavaScript, closures are created every time a function is created, at function creation time.
>Scoping with let and const

>Traditionally (before ES6), JavaScript only had two kinds of scopes: function scope and global scope. Variables declared with var are either function-scoped or global-scoped, depending on whether they are declared within a
>function or outside a function. This can be tricky, because blocks with curly braces do not create scopes:
# Why do we have closures in JavaScript?
Am wrapping my head around JavaScript closures and am at a point where things are falling in place; i.e a closure is the local variables for a function - kept alive after the function has returned, or a closure is a stack-frame which is not deallocated when the function returns.

Am starting to understand this concept, but the more i understand the more i keep on wondering why do we have to use them
