## Control Flow


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


### Research


#### Statements and delarations:
> [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)


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
