## Self Study
#### June 27th

**The Increment Operator**
The increment `++` and decrement `--` operators work the same way so everything I am saying in reference to increment applies to decrement. The operator `++` can be applied before or after the base (variable name) and where you put them makes a difference in how the operation is run.

*First we have to understand what ++ means*
- it is not by default var = var + 1
- the actual expression of the operation is dependant on the increment preceding or following the variable
- it includes a return value

When we use var++ we are telling the computer
> Return the current value of i, then make var + 1 the new value 

When we use ++var we are telling the computer
> make var + 1 the new value, return the new value

So in practice here are the differences

**i++**
> let i;

> let j = i++;

> *the current value of i is returned and assigned to j and then the expression is evaluated, the value of i increases by 1 and is assigned to i*

> *now j has the value 1, and i has the value 2*

**++i**
> let i;

> let j = ++i;

> *i + 1 is evaluated and assigned to i, which is returned and assigned to j*

> *now j and i both have the value 1*

In the case of a for loop either operator works because the increment statement is not evaluated until *after* the condition is evaluated and the statement executes. The loop is restarted with the new value of i.

[Return Home](https://sarabeth-russert.github.io/reading-notes/)
