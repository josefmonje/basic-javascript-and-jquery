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
