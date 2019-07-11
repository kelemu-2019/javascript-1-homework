> paste [this markdown](https://raw.githubusercontent.com/janke-learning/error-exercises/master/arrays.md) into this file and fix the errors!    
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/errors_solutions.MD)  (of the old version)  
> references: [errors & life-cycle](https://github.com/janke-learning/errors-and-life-cycle), [exercise repo](https://github.com/janke-learning/errors)
# Array Errors


* [missing closing bracket](#missing-closing-bracket)
* [missing comma](#missing-comma)
* [poorly nested](#poorly-nested)

---

## missing closing bracket

broken code:
```js
let myArray = [1, 2, 3;

```
error message:
```
 Unexpected token ;
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

it is creation phase and syntax error
the fix:
```js
  let myArray = [1, 2, 3];
```
your notes:

[TOP](#array-errors)

---

## missing comma

broken code:
```js
let myArray = [1, 2 3];
```
error message:
```
Unexpected number
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?
creation phase and syntax and semanitc
the fix:
```js
let myArray = [1, 2, 3];
```
your notes:

[TOP](#array-errors)

---

## poorly nested

broken code:
```js
let myArray = [
                [1, 2, 3]
                [4, 5, 6]
                [7, 8, 9]
              ];
```
error message:
```
redeclaration of let myArray
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?
creation phase and Syntax 
the fix:
```js
let otherName = [[1, 2, 3], [4, 5, 6], [7, 8, 9] ];
```
your notes:

[TOP](#array-errors)


___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
