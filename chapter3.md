# Objects

In JS, everything is an object.

* Number
* String
* Boolean
* Object
* *Array*
* *Function*
* *null* - has a value but the value is null
* undefined - has no assigned value

```
var length = 11                            // Number
var lastName = "11"                        // String
var y = false || true                      // Boolean

var x = {firstName:"John", lastName:"Doe"} // Object
x.gender = "Male"                          // adding a property
delete x.gender                            // delete a property
x["gender"] = "Male"                       // can also use array syntax
x.fullName = function(){                   // method that returns full name
  return x.firstName + " " + x.lastName
}

var cars = ["Honda", "Toyota", "BMW"]      // Array (object)
cars[0]                                    // access array value on index 0
cars[3] = "Ford"                           // create new array value on index 3
cars[5]                                    // cars[4] will be undefined
delete cars[0]                             // cars[0] will be undefined

var u                                      // undefined
var u = undefined                          // undefined
```
> *Assigning various JS data types to variables*


#### Converting strings to numbers

In case of numbers being represented as strings (`"1"` as opposed to `1`), JS has methods to convert them back to numbers:

* parseFloat() and parseInt() 
* or use `+`

```
"1.1" + "1.1" = "1.11.1"
+"1.1" + +"1.1" = 2.2 
```
> *Using `+` on numbers with string as their data type*


### Research


#### Strings:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)


#### Numbers:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)


#### Arrays:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)


#### Objects:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)


#### Built-in objects:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects)


### Next

* Learn what operators are available for your logic