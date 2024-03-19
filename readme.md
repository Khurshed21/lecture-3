# What is Recursion
# In Javascript

Recursion is a programming pattern or concept embedded in many programming languages, and JavaScript is not left out. It is a feature used in creating a function that keeps calling itself but with a smaller input every consecutive time until the code's desired result from the start is achieved.
___

![](https://javascript.info/article/recursion/recursion-pow.svg)
___
``` javascript
function recurse() {
    // function code
    recurse();
    // function code
}

recurse();
```
___
# What is Closure
# In JavaScript

A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function.
___
![](https://dmitripavlutin.com/static/00b6ed6d91a74c2e4ca5096e2d541dd7/59014/cover-5.png)
___
```javascript
function myFunction() {
  let a = 4;
  return a * a;
}


