# Week 2 Day 1
__12/07/2020__

## What is Scope?
Scope is the range of a variable of function. If you have a variable outside of a function, it would have global scope, meaning it could be accessed from in a function or out of a function. You could also have two variables in two seperate functions have the same name, such as x. Because they are in the local scope of the functions, they wont interact or override each other.

## what is Hoisting
Hoisting is the idea that even if you put a variable at the end of a function, it can be "hoisted" up to the top of the function. Const, Var, and Let are all hoisted variable keywords. This allows your function to still work even though your variables could be after the function itself.

## In what cases might you use let vs const vs var?
Let is able to be changed locally and globally. Const is not able to be changed at all. Var is block scoped and can be updated, but not redeclared. This all means that each of the optionss can be used for different things, such as, if you know that x will always have a value of 1, you could use const. If you need to update a variable globally, var would be a good use for that. Let would be used in most cases since its block can have varrying sizes.
