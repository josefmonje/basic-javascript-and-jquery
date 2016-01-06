# The Document Object Model

Sample code in "vanilla" JavaScript:

```
element = document.getElementById("id")
element = document.getElementByClass("class")
element = document.querySelector("css selector")
element = document.querySelectorAll("css selector")
```
> *Selecting HTML elements with JS*

```
element.innerHTML = "string"
element.innerHTML = "<h1>string</h1>"

element.style.display = 'none'
element.style.visibility = 'hidden'
```
> *Manipulating HTML elements with JS*

```
window.onload = function () {
  init()
  doSomethingElse()
}
```
> *Events*


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
          <a href="#" title="click here!">This is a link</a>
          <img src="http://placehold.it/100x50/?text=image" alt="Alt text" width="100" height="50">
        </div>
      </div>
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
