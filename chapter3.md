## Logic Control


### If Statements

```
if (expression evaluates as true) {
  doSomething()
}

if (true) {
  doSomething()
} else {
  doSomethingElse()
}

if (true) {
  doSomething()
} else if (anotherCondition) {
  doAnotherThing()
} else {
  doSomethingElse()
}
```
> *If ...else Statements*


```
for (var i = 0; i < Array.length; i++) {
  Array[i]
}

for (var i = Array.length-1; i >= 0; i--) {
  Array[i]
}
```
> *For loops*


### Research


#### Statements and delarations:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)


#### Operators:

Assignment (`=`)

Arithmetic (`+`, `-`, `*`, `/`, `%`, `++`, `--`)

* Use + on strings to concatenate
* Concatenating strings and numbers changes type to string
* The Arithmetic and the Assignment operators can be used in conjunction

Comparison (`==`, `===`, `!=`, `!==`, `<`, `>`, `<=`, `>=`)

```
// typeof keyword
typeof undefined   // undefined
typeof null        // object
null == undefined  // true - both have no value assigned
null === undefined // false - they are not of the same type
```
> *Using `typeof`, `==` and `===` to compare `null` and `undefined`*

Logical (`&&` for And, `||` for Or)
```
var y = false || true // Boolean
y == true
```
> *Using `||` in variable assignments*

Ternary (`(expression) ? (if true) : (if false)`)
```
y == true ? console.log('yes') : console.log('no')
```
> *Example using a ternary operator*


#### Expressions and Operators:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators)


### Functions

* Functions represent blocks of code
* May be named or anonymous
* May or may not accept arguments
* May or may not return values
* Can be defined in several ways


#### Defining and calling functions:

```
function func () {} // spaces are ignored but make code more readable
function func(arguments){
  /*
  do something
  something = arguments + arguments
  can also return something
  */
  return something
}

func()          // function "func" is called
func(arguments) // with arguments

function () {
  // I'm an anonymous function
}

var f = func()       // contains values returned from func() 
var f = func() {}    // assigns a function
var f = func(args) { // assigns a function returns arguments passed to it
  return args
}
var f = func         // the function definition is assigned
f()                  // calls the function
```
> *Variable assignment and functions*


#### Functions:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function)


### Exercises

* FizzBuzz
  * Write a function that accepts a number as its parameter
  * The function will loop as many times as that number
  * The console will:
    * print FIZZ if the number is divisible by 3
    * print BUZZ if the number is divisible by 5
    * print FIZZBUZZ! if the number is divisible by both 3 and 5
    * or print the number if none of the above

```
0
1
2
FIZZ
4
BUZZ
FIZZ
7
8
FIZZ
BUZZ
11
FIZZ
13
14
FUZZBUZZ!
```
> *Desired FizzBuzz output*


### Interacting with the Document Object Model or DOM

Sample code in "vanilla" JavaScript:

```
element = document.getElementById("id")
element = document.getElementByClass("class")
element = document.querySelector("css selector")
element = document.querySelectorAll("css selector")

element.innerHTML = "string"
element.innerHTML = "<h1>string</h1>"

element.parentNode

element.style.display = 'none'
element.style.visibility = 'hidden'

window.onload = function () {
  init()
  doSomethingElse()
}
```
> *Selecting and manipulating HTML elements with JS*


### Example

```
<!DOCTYPE html>
<html>
  <body>
    <div class="container">
      <div class="row">
        <div id="header" class="col-md-6" >
          <h1>This is a Heading</h1>
          <p>This is a paragraph.</p>
        </div>
        <div id="image" class="col-md-6">
          <a href="#" title="click here!">This is a link</a>
          <img src="http://placehold.it/100x50/?text=image" alt="Alt text" width="100" height="50">
        </div>
      </div>

    <script type="text/javascript">
    var element = document.getElementById("button")
    element.addEventListener('click', changeBGWhite, false)

    var changeBGWhite = function () {
      document.body.style.backgroundColor = "White"
    }

    function changeBGBlue () {
      document.body.style.backgroundColor = "blue"
    }

    window.onload = function () {
      changeBGBlue()
    }
    </script>

  </body>
</html>
```
> *Changing CSS with JS*


### Exercises

* Create a calculator in HTML and JS
* Create a calculator in HTML and JS without using ```eval```

While starting out, you'll likely encouter errors. Read them and try to understand what it says. Read you code and check if you see what's wrong. Search for it online - you're not the first one to encounter it. The answer is out there.

#### Document object
> [https://developer.mozilla.org/en-US/docs/Web/API/Document](https://developer.mozilla.org/en-US/docs/Web/API/Document)


### Exercises

* Create personal webpage using Bootstrap and at least 3 of its JS components
* Demonstrate the use of other non-jQuery 3rd party JS libraries


### Recap

* JavaScript is the programming language of web browsers.
* JavaScript lets you add interactivity to your website.


### Next

* Learn how to use jQuery


#### FizzBuzz Solution:

```
function FizzBuzz (n){
  for (var i = n; i >= 0; --i) {
    if ((i % 5 == 0) && (i % 3 == 0)) {
      console.log("FizzBuzz!")
    } else if (i % 3 == 0) {
      console.log("Fizz")
    } else if (i % 5 == 0) {
      console.log("Buzz")
    } else {
      console.log(i)
    }
  }
}
```
