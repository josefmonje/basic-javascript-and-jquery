# Functions

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


### Research


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

---


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
