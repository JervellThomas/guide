---
title: Use Destructuring Assignment to Assign Variables from Objects
---
## Use Destructuring Assignment to Assign Variables from Objects

# This challenge requires some intuition about string objects in javascript. 

When you create a string object it is based on the following <a>https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/prototype>string prototype</a>. 
Thus, each string has a length property; genericString = {length: 13}. (This is the only adopted property from the String.prototype.)

# Reassign properties using deconstruction. 
var basicOjb = {x: 40};
//To reassign 'get the value of x and place its value into bigX' in ES6:
const { x: bigX } = basicOjb;
consle.log(bigX) // 40 

# Put the value of the length property of 'str' into len.
