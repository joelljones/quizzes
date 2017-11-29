# Quiz: DOM Scripting

__1. Each element of the DOM is best known as a what?__

  - [x] node
  - [ ] object
  - [ ] item
  - [ ] target

  ---

__2.__

    window.addEventListener('scroll', function(event) {
      console.log(event);
    });

  __What is "scroll" in this context?__

  - [ ] an event to trigger

  - [ ] a function to execute

  - [x] an event to listen for

  - [ ] none of these

  __EXPLANATION__

  The .addEventListener() method takes two required arguments, `type` and `listener`. `Type` is a string representing the type of event to listen for, and `listener` is the function to fire when the event has been triggered.

  ---

__3. If the event handlers are set to bubble, what happens when the user clicks on element 1?__

    ------------------------------------
    | document                         |
    |   ---------------  ------------  |
    |   | element1    |  | element2 |  |
    |   ---------------  ------------  |
    |                                  |
    ------------------------------------

    element1.onclick = doSomething;
    element2.onclick = doSomething;
    document.onclick = defaultFunction;

  - [ ] `doSomething()` is executed.

  - [ ] `defaultFunction()` is executed.

  - [x] `doSomething()` is executed. `defaultFunction()` is executed.

  - [ ] `doSomething()` is executed. `doSomething()` is executed. `defaultFunction()` is executed.

  __EXPLANATION__

  In event bubbling, after an event triggers on the deepest possible element, it then triggers on parents in nesting order.

  The opposite of bubbling is capturing, when the parent elements are triggered before the target element. The `EventTarget.addEventListener()` defaults to bubbling. You will need to set the `useCapture` parameter to `true` to enable capturing.

  ---

__4. If you insert JavaScript directly into an HTML document with the `<script>` tag, where should you put it to make sure it runs after the page loads?__

  - [ ] Just after the `<head>` tag.

  - [ ] Just after the `<body>` tag.

  - [x] Just before the closing `</body>` tag.

  - [ ] Just before the closing `</html>` tag.

  __EXPLANATION__

  Browsers read HTML files from the top down. Although scripts can be placed anywhere in a file, we've placed the `<script>` tags at the end of the document. This makes the page appear to load faster to the end user because the JavaScript is not blocking the content from rendering.

  ---

__5. Which event occurs when the user clicks on an HTML element?__

  - [x] onclick
  - [ ] onchange
  - [ ] onmouseover
  - [ ] onmouseclick

  ---

__6. Using no helper libraries, just DOM scripting, what do you use to change the style of an element?__

  - [ ] `.css()`

  - [x] `.style`

  - [ ] `.transform()`

  - [ ] None of the above

  __EXPLANATION__

  `.css()` is a jQuery method, while `.style` is used with vanilla DOM scripting.

  ---

__7. What is the correct HTML to include a JavaScript library?__

  - [ ] `<script href="mylibrary.js"></script>`
  - [ ] `<link type="script" src="mylibrary.js">`
  - [ ] `<link rel="script" href="mylibrary.js">`
  - [x] `<script src="mylibrary.js"></script>`

  ---

__8. What of the following is true of HTML `data-*` attributes?__

  - [ ] It needs to have a defined meaning.
  - [ ] The data is accessible by assistive technology.
  - [ ] It should be used to store data that is visible to the user.
  - [x] It can be added as an attribute to any HTML tag to store extra information.

  ---

__9. What is the correct JavaScript syntax to change the content of the specific HTML element below?__

`<p id='demo'>This is a demonstration.</p>`

  - [x] `document.getElementById('demo').textContent = 'Hello World!';`

  - [ ] `document.getElement('p').textContent = 'Hello World!';`

  - [ ] `#demo.textContent = 'Hello World!';`

  - [ ] `$(document).textContent = 'Hello World!';`

  __EXPLANATION__

  Because there may be multiple `<p>` elements, we want to target this element specifically by it’s ID using `getElementbyID()`.
