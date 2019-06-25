> paste [this markdown](https://raw.githubusercontent.com/janke-learning/errors/master/functions.md) into this file and fix the errors!  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/errors_solutions.MD) (of the old version)  
> references: [errors & life-cycle](https://github.com/janke-learning/errors-and-life-cycle), [exercise repo](https://github.com/janke-learning/errors)

# Function Errors

* [missing arguments](#missing-arguments)
* [is not a function](#is-not-a-function)

---

## missing arguments

broken code:
```js
function getNine {
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
error message:
```
SyntaxError: missing ( before formal parameters
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

syntax and creation
the fix:
```js
function getNine() {
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
your notes: Function declered without parentacies

[TOP](#function-errors)
Mising Parentecise (improper function decleration)
---

## is not a function

broken code:
```js
let array = [];
array.length()
```
error message:
```
redeclaration of let array
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?
creation phase  annd semanitc
the fix:
```js
let xy = [];
xy.length;
```
your notes:

using the array as a function

[TOP](#function-errors)

# Function Errors

* [missing arguments](#missing-arguments)
* [is not a function](#is-not-a-function)

---

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
