# Quiz: CSS Selectors

1. What will be the color of the links after applying the CSS below?

  ```css
  body {
   color: green;
  }

  .main-content a {
    color: blue;
  }

  a {
   color: red !important;
  }
  ```

  - [x] Red
  - [ ] Green
  - [ ] Black
  - [ ] Blue

1. What is the correct syntax to select an HTML element inside another HTML element?

  - [x] `.main-list li {}`
  - [ ] `li.main-list {}`
  - [ ] `.main-list, li {}`
  - [ ] `.main-list + li {}`

1. Which of the following best describes the concept of CSS selector specificity?

  - [ ] Specificity refers to whether you write an ID, class, or tag selector.
  - [x] Specificity refers to how a browser decides which styles to display when there are multiple styles defined for the same element.
  - [ ] Specificity refers to whether the `!important` tag is used.
  - [ ] Specificity refers to the order in which HTML elements appear in the browser immediately after rendering.

1. Which of the following statements is correct?

  - [ ] Tags are more specific than IDs and classes.
  - [x] IDs are more specific than classes and tags.
  - [ ] Multiple classes are more specific than IDs and tags.
  - [ ] Classes are more specific than IDs and tags.

1. What is the most specific selector in the code below?

  ```css
  p {

  }

  #side-bar {

  }

  .main-content {

  }

  .main-content p {

  }
  ```

  - [x] `#side-bar`
  - [ ] `p`
  - [ ] `.main-content`
  - [ ] `.main-content p`

1. What is the correct syntax to style multiple unrelated selectors?

  - [ ] `.nav-menu; p {}`
  - [ ] `.nav-menu p {}`
  - [x] `.nav-menu, p {}`
  - [ ] `p.nav-menu {}`
