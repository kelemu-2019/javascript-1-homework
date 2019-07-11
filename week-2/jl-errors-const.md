> paste [this markdown](https://raw.githubusercontent.com/janke-learning/error-exercises/master/const.md) into this file and fix the errors!      
> references: [errors & life-cycle](https://github.com/janke-learning/errors-and-life-cycle), [exercise repo](https://github.com/janke-learning/errors)

# Variable Errors


### exercises
* [missing variable name](#missing-variable-name)
* [reassigning to constant](#reassigning-to-constant)
* [unassigned const declaration](#unassigned-const-declaration)

---

### missing variable name

broken code:
```js
const = 5;
```
error message:
```js
missing variable name
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

it is creation phase 
the fix:
```js
const x=5;
```
your notes:

[TOP](#variable-errors)

---


## reassigning to constant

broken code:
```js
const a = 9;
a = 0;
```
error message:
```
invalid assignment to const `a'
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?
creation phase and semantic 
the fix:
```js
const = 0;
```
your notes:

[TOP](#variable-errors)

---


## unassigned const declaration

broken code:
```js
const a;
a = 0;
```
error message:
```
missing = in const declaration
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?
creation phase
the fix:
```js
const a = 0;
```
your notes:

[TOP](#variable-errors)

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
