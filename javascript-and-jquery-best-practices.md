# Quiz: JavaScript and jQuery Best Practices

__1. To change the text color of all `div`s to red using jQuery, what goes in the blanks?__

`$('div').css(_______, _______);`

  - [x] 'color', 'red'

  - [ ] 'red', 'color'

  - [ ] color, red

  - [ ] red, color

  __EXPLANATION__

  The jQuery syntax is `.css(propertyName, value)`.

  `propertyName` has a type of `string`. `value` has a type of `string` or `number`. Strings require quotation marks around the string.

  ---

__2. The following description best describes which jQuery method?__

  jQuery's shorthand for an event that handles both `mouseenter` and `mouseleave` behavior.

  - [ ] `.click()`

  - [ ] `.find()`

  - [ ] `.get()`

  - [x] `.hover()`

  __EXPLANATION__

  The `.hover()` method binds one or two handlers to the matched elements, to be executed when the mouse pointer enters and leaves the elements.

  ---

__3. How would you rewrite the following JavaScript in jQuery?__

    var domElement = document.getElementById('refrigerator');
    domElement.style.color = 'white';

  - [ ] `$('.refrigerator').css('style', 'white');`
  - [ ] `$('#refrigerator').style('white');`
  - [x] `$('#refrigerator').css('color', 'white');`
  - [ ] `$('.refrigerator').style('color', 'white');`

  ---

__4. What is the correct jQuery code to set the background color of all `p` elements to `red`?__

  - [x] `$('p').css('background-color','red');`
  - [ ] `$('p').style('background-color','red');`
  - [ ] `$('p').manipulate('background-color','red');`
  - [ ] `$('p').layout('background-color','red');`

  ---

__5. How do you find the number with the highest value of x and y?__

  - [ ] Math.ceil(x, y)
  - [x] Math.max(x, y)
  - [ ] top(x, y)
  - [ ] ceil(x, y)

  ---

__6. In the following code, what information is stored in the variable `distanceX` when the event fires?__

  `var distanceX = event.pageX;`

  - [x] The distance between the mouse and the left edge of the browser window.

  - [ ] The distance between the mouse and the right edge of the browser window.

  - [ ] The width of the browser window.

  - [ ] The height of the browser window.

  __EXPLANATION__

  `pageX` is a property on jQuery events that stores the location of the X coordinate where an event occurs in the browser window.

  ---

__7. Which of the following comparisons returns `false`?__

  - [ ] '17' == 17
  - [ ] 92 === 92
  - [x] false == 1
  - [ ] "\n \n \t" == 0

  ---

__8. To select all elements using jQuery with the id name 'punch' that have a parent element with the 'fruit' class name we would write:__

  - [x] `$('.fruit #punch')`
  - [ ] `$(.fruit #punch)`
  - [ ] `$(#punch .fruit)`
  - [ ] `$('#punch .fruit')`

  ---

__9. Which of the following is an example of an anonymous closure?__

    // Sample A
    function example() {
      alert('Example!');
    }

    example();

    // Sample B
    (function() {
      alert('Example!');
    })()

    // Sample C
    (function example() {
      alert('Example!');
    })

  - [ ] Sample A
  - [x] Sample B
  - [ ] Sample C
  - [ ] None of the above

  ---

__10. During the deployment of your application through Git, you want certain files to be ignored. Which of the following files performs that operation?__

  - [ ] config.ru
  - [ ] Gemfile
  - [ ] Rakefile
  - [x] .gitignore

  ---

__11. Using the jQuery selector `$('div.intro')`, what will be selected?__

  - [x] All `div` elements with `class='intro'`.
  - [ ] All `div` elements with `id='intro'`.
  - [ ] The first `div` element with `id='intro'`.
  - [ ] The first `div` element with `class='intro'`.
