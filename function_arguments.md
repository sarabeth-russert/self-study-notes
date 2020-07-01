## Self Study
#### June 30th

**Function Parameters and Arguments**
- Parameters are the names listed in the function definition.
- Arguments are the real values passed into the function call.

In javascript the type of information does not need to be defined by the functions parameters. You can even pass more or less arguments than is defined when creating the function. Arguments can be either passed by value or passed by reference depending on the type of information an argument is.
- Primitive types like strings, numbers, boolean, null, and undefined are passed by value.
- Objects and Arrays are passed by reference

In the case of arguments that are passed by value anything done to the passed value within the function does not affect the variable outside the scope of the function. This is because the function was passed a copy of the value of the variable.

In the case of an object or array that is passed by reference into a function anything that is altered in the object within the function is reflected in the object even outside the scope of the function. This is because the function is being given a variable that points directly to the original object to use for the function, not a copy.

When an equation is passed as an argument into a funtion the argument is first evaluated and then the function is invoked. So in the case of an argument like i++ the argument is evaluated. The value of i is returned, the increment applied, and then the function is invoked with the new value of i.

There is also a special feature of functions in javascript called the Aruguments Object.
>*arguments* is an Array-like object accessible inside functions that contains the values of the arguments passed to that function.

When a function is invoked and arguments are passed they are stored on the stack inside the arguments object. You can access them by index number or with the three properties
- `arguments.callee`
- `arguments.length`
- `arguments[@@iterator]`



[Return Home](https://sarabeth-russert.github.io/reading-notes/)
