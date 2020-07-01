## Self Study
#### June 30th

**Function Parameters and Arguments**
- Parameters are the names listed in the function definition.
- Arguments are the real values passed into the function call.

In javascript the type of information passed does not need to be defined by the functions parameters. You can even pass more or less arguments than is defined when creating the function. Arguments are always passed by value in javascript.

In the case of arguments that are primitive types *like strings, numbers, boolean, null, and undefined* anything done to the passed value within the function does not affect the variable outside the scope of the function. This is because the function was passed a copy of the value of the variable.

In the case of an object or array the value passed is a pointer or reference to the space that the object holds in memory. If a change is made to the object (or array) within the function it can change the object outside of the function. This can only occur by refering directly to the part of the object you want to change using a specific pointer, in the case of an object the objectName.propertyKey, in the case of array the properties like index, push, splice, slice, etc can modify the array.

When an equation is passed as an argument into a funtion the argument is first evaluated and then the function is invoked. So in the case of an argument like i++ the argument is evaluated. The value of i is returned, the increment applied, and then the function is invoked with the new value of i.

There is also a special feature of functions in javascript called the Aruguments Object.
>*arguments* is an Array-like object accessible inside functions that contains the values of the arguments passed to that function.

When a function is invoked and arguments are passed they are stored on the stack inside the arguments object. You can access them by index number or with the three properties
- `arguments.callee`
- `arguments.length`
- `arguments[@@iterator]`



[Return Home](https://sarabeth-russert.github.io/reading-notes/)
