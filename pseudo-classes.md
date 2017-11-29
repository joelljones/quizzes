# Quiz: Pseudo-classes

1. What would be the outcome of the following pseudo class selector?

  `a:nth-child(3n + 2)`

  - [ ] The pseudo-class selector would select every second link, starting with the second.
  - [ ] The pseudo-class selector would select every third link, starting with the third.
  - [x] The pseudo-class selector would select every third link, starting with the second.
  - [ ] The pseudo-class selector would select every second link, starting with the third.

1. Which of the following would modify only the first list element within an unordered list?

  ```css
  ul li:first-child {
    color: gray;
  }
  ```
  ```css
  ul li:last-child {
    color: gray;
  }
  ```
  ```css
  ul li:nth-child {
    color: gray;
  }
  ```
  ```css
  ul li:1n + n {
    color: gray;
  }
  ```
  - [x] a
  - [ ] b
  - [ ] c
  - [ ] d

1. Which best describes pseudo-class selectors?

  - [ ] Pseudo-class selectors style specific parts of an individual element, such as the first letter or line of an element.
  - [x] Pseudo-class selectors style selected elements based on user interactions and context within a web document.
  - [ ] Pseudo-class selectors style selected elements based on the frequency of the element on the page.
  - [ ] Pseudo-class selectors style specific elements based on the element's uniqueness.

1. Which of the following is _not_ a dynamic pseudo-class selector?

  - [x] `:optional`
  - [ ] `:visited`
  - [ ] `:link`
  - [ ] `:active`

1. Which of the following is NOT a valid nth-child pseudo-class selector?

  - [ ] `a:nth-child(1n + even)`
  - [ ] `a:nth-child(1n + 2)`
  - [ ] `a:nth-child(odd)`
  - [ ] `a:nth-child(even)`

1. What is a structural pseudo-class selector?

  - [ ] It styles an element based on its size.
  - [ ] It styles the entire HTML document as whole in a single selector.
  - [x]

  It styles an elements based on its context within an HTML document.
  - [ ] It allows us to modify the HTML directly, by inserting new HTML tags in place of old HTML tags.

1. Which correctly represents the 'an + b' pattern of the nth-child selector?

  - [ ] `a` represents the index of each selected element. `n` is a variable represents the multiple of elements we want to select. `b` represents the first element we want to start the pattern on.
  - [ ] `a` represents the multiple of elements we want to select. `n` is a variable that represents the first element we want to start the pattern on. `b` represents the index of each selected element.
  - [x] `a` represents the multiple of elements we want to select. `n` is a variable that represents the index of each selected element. `b` represents the first element we want to start the pattern on.
  - [ ] `a` represents the first element we want to start the pattern on. `n` is a variable that represents the index of each selected element. `b` represents the multiple of elements we want to select.

1. If implemented, this code block would result in which of the following outcomes?

  `a:nth-child(5n + 0)`

  - [ ] It would style every element, starting at the fifth element.
  - [ ] It would style every fifth element, starting at the first element.
  - [x] It would style every fifth element, starting at the fifth element.
  - [ ] It would style every fifth element, starting at the second element.

1. Which most accurately describes the function of the `:active` pseudo-class selector?

  - [ ] It styles an element when a user hovers over the element with a cursor.
  - [ ] It styles a visited link.
  - [x] It styles an element when the the user enables the element, specifically the time between a user clicking on an element and releasing the mouse.
  - [ ] It styles an element that is an active link that can be pressed on.

1. Which represents the correct syntax for a pseudo-class selector?

  ```css
  ul li:active: {
    color: lightblue;
  }
  ```
  ```css
  ul:active li {
    color: lightblue;
  }
  ```
  ```css
  ul li:active {
    color: lightblue;
  }
  ```
  ```css
  :active {
    color: lightblue;
  }
  ```
  - [ ] a
  - [ ] b
  - [x] c
  - [ ] d
