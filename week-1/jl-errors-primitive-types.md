> paste [this markdown](https://raw.githubusercontent.com/janke-learning/errors/master/primitive-types.md) into this file and fix the errors!  
> [completed example](https://github.com/AlfiYusrina/hyf-javascript1/blob/master/week1/errors_solutions.MD)  (of the old version)  
> references: [errors & life-cycle](https://github.com/janke-learning/errors-and-life-cycle), [exercise repo](https://github.com/janke-learning/errors)

# Primitive Type Errors

* [improper multi-line string](#improper-multi-line-string)
* [improper nested quotes 1](#improper-nested-quotes-1)
* [improper nested quotes 2](#improper-nested-quotes-2)

---

## improper multi-line string

broken code:
```js
let a = 'this is 
two lines';
```
error message:
```
SyntaxError: '' string literal contains an unescaped line break
```
classification:
* creation phase or execution phase ?

* syntax or semanitc ?

creation phase  and Synatx
the fix:
```js
let a = 'this is \"two lines\"';
```
your notes:

[TOP](#primitive-type-errors)

---

## improper nested quotes 1

broken code:
```js
let innerHtml = "<p>Click here to <a href="#Home">return home</a></p>";
```
error message:
```
SyntaxError: fields are not currently supported
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

creation and syntax
the fix:
```js
let innerHtml = '<p>"Click here to" <a href="#Home">return home</a></p>';
```
your notes:
 improper uses of single  and double quet
[TOP](#errors)

---

## improper nested quotes 2 

broken code:
```js
let nested_messages = 'remind yourself ''i can do this!'' at least once a day';
```
error message:
```
 unexpected token: string literal
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

* 
the fix:
```js
let nested_messages = "remind yourself '\i can do this!'\ at least once a day";
```
your notes:
Misplaced used of single and double quets
[TOP](#primitive-type-errors)

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>


