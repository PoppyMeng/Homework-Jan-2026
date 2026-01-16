1. What is dynamic typing?
Dynamic typing means a variable’s type is determined at runtime rather than at compile time. In JavaScript, a variable can hold different types of values at different times without explicit type declarations.

2. Explain the difference between var, let, & const.
var is function-scoped and can be redeclared, which may cause unexpected behavior. let and const are block-scoped, but const cannot be reassigned after initialization, while let can.

3. What is immutability? What data types in JS are immutable?
Immutability means a value cannot be changed after it is created. In JavaScript, primitive types like string, number, boolean, null, undefined, symbol, and bigint are immutable.

4. What is the difference between == and ===?
== performs type coercion before comparison, which can lead to unexpected results. === checks both value and type, making it the safer and more predictable option.

5. What are some examples of falsy values in JS?
Falsy values are values that evaluate to false in a boolean context. Examples include false, 0, "" (empty string), null, undefined, and NaN.

6. Explain hoisting in JavaScript.
Hoisting is JavaScript’s behavior of moving variable and function declarations to the top of their scope during compilation. Variables declared with var are hoisted and initialized as undefined, while let and const are hoisted but not initialized.

7. Explain variable shadowing in JavaScript.
Variable shadowing occurs when a variable in a local scope has the same name as one in an outer scope. The inner variable “shadows” the outer one, making the outer variable inaccessible within that scope.

8. What is a callback function?
A callback function is a function passed as an argument to another function. It is executed later, often after an asynchronous operation or event completes.

9. What’s the difference between primitive data types and reference data types in JS?
Primitive data types store simple values and are passed by value. Reference data types like objects and arrays store references in memory and are passed by reference.

10. What’s the difference between array for loop and forEach?
A for loop gives more control, allowing you to break or continue the loop. forEach is a higher-order function that iterates over arrays but cannot be exited early.

11. What’s the difference between array map and forEach?
map returns a new array with transformed elements. forEach does not return a new array and is typically used for side effects.

12. What is the difference between array slice and splice?
slice returns a shallow copy of a portion of an array without modifying the original. splice changes the original array by adding, removing, or replacing elements.

13. What is ‘use strict’? What are the major effects that it has?
"use strict" enables strict mode, which enforces safer coding practices. It prevents the use of undeclared variables, disallows duplicate parameter names, and makes certain errors throw exceptions.

14. What is an arguments object?
The arguments object is an array-like object available inside non-arrow functions. It contains all the arguments passed to the function, even if they are not explicitly defined as parameters.