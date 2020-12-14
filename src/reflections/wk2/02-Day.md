# Week 2 Day 2
__12/08/2020__

## What are three ways to synactically write a function? What are the differences in how the function acts (if any)?
A function can be named (function name(paramaters){}), it can be an anonymous function set to a variable(let name = function(paramaters){}), and a there are arrow function expressions (let name= (paramaters) => {}). Functions that are defined are hoisted, allowing them to be used before tjhey are actually definted, while the anonymous and arrow functions are not hoisted and have to be tied to a variable in order to be called seperately.

## What is the difference between Paramaters and Arguments?
Paramaters are what the function is expecting to recieve while arguments are the actual item passing through the function. The paramater is simply telling the function to treat the argument as whatever the parameter is set to.

## What are higher order functions? can you provide an example?
Higher order functions are functions that accept another function as its parameter. There are a lot of examples, but one could be array.map(item=>item*2). This function would give us a multiplied version for each item in the array as it loops through.