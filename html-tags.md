# Quiz: HTML Tags

1. What needs to be added to the opening tag of an element to be able to use it as an anchor that links to a different section of the same page?

  - [ ] `#id`
  - [x] `id="target"`
  - [ ] `#target`
  - [ ] `id=#target`

1. The following code creates a link to another page. Which of the following will cause the page to open in a new browser window?

  ```html
  <a href="https://codecademy.com">Codecademy</a>
  ```

  - [ ] The URL should include "new_window" at the end of it.
  - [ ] Single quotation marks should be used instead of double quotation marks.
  - [x] Add the `target` attribute, with its value set to `_blank`.
  - [ ] Wrap the `<a>` tag with a `<window>` tag.

1. Which of the following would create a link to a local HTML file called aboutme.html?

  - [ ] `<a href="https://aboutme.com/">About Me</a>`
  - [ ] `<a href="https://aboutme.com/" />`
  - [x] `<a href="./aboutme.html">About Me</a>`
  - [ ] `<a href="./aboutme.html" />`

1. How many different heading elements does HTML support?

  - [ ] 1
  - [x] 6
  - [ ] 9
  - [ ] 3

1. How would the output of the code below change if `<ul> `and `</ul>` were changed to `<ol>` and `</ol>`, respectively?

  ```html
  <ul>
    <li>Lorem</li>
    <li>Ipsum</li>
    <li>Horribilis</li>
  </ul>
  ```

  - [ ] The code would no longer output any visible content in the browser.
  - [ ] No changes to the output would occur.
  - [ ] Numbers in the output would change to bullet points.
  - [x] Bullet points in the output would change to numbers.

1. The following code is supposed to create a link to another web page, but fails to do so. Why?

  ```html
  <a>Codecademy</a>
  ```

  - [x] The `<a>` element is missing the `href` attribute set to the URL of the Codecademy website.
  - [ ] The `<a>` element should be replaced with a `<link>` element.
  - [ ] The word "Codecademy" should be replaced with the URL to the Codecademy website.
  - [ ] The `</a>` closing tag should be removed.

1. Which of the following elements will directly affect the vertical spacing in an HTML layout?

  - [ ] `<break />`
  - [x] `<br />`
  - [ ] `<b>`
  - [ ] `<break>`

1. The following code is supposed to display an image, but fails to do so. Why?

  ```html
  <img https://www.example.com/laptop.jpg />
  ```

  - [x] The `src` attribute is missing and must be set equal to the image URL, enclosed in double quotation marks.
  - [ ] The `<img>` tag can only display .png or .svg image formats.
  - [ ] The image URL should be all uppercase.
  - [ ] The `<img>` tag should be replaced with an `<image>` tag.

1. What HTML code will most web browsers display as italics?

  - [ ] `<strong>Hello</strong>`
  - [ ] `<div>Hello</div>`
  - [x] `<em>Hello</em>`
  - [ ] `<p>Hello</p>`

1. The following code results in no visible output to the browser. Why?

  ```html
  <ol>

  </ol>
  ```

  - [ ] The `<ol>` tag signifies "old" information, meaning the contents will never display.
  - [ ] `<ol>` is not a valid HTML element.
  - [x] List items must be added to the list.
  - [ ] The `<ol>` tag must be replaced with a `<ul>` tag.

1. Which tag should you use to indicate to the browser that a group of links is the navigation bar for the website?

  - [x] `<nav>`
  - [ ] `<navigation>`
  - [ ] `<a>`
  - [ ] `<link>`

1. Why is the code below incorrect?

  ```html
  <video src="myVid.mp4" controls >
  ```

  - [ ] A valid self=closing tag ends with `/>`.
  - [ ] The `myVid.mp4` video source (`src=`) is not valid.
  - [ ] The width and height of the video must be specified.
  - [x] The video element is not a self-closing tag. It should have an opening and a closing tag.

1. Which of the following tags can be used to add a paragraph to a web page?

  - [x] `<p>`
  - [ ] `<info>`
  - [ ] `<text>`
  - [ ] `<paragraph>`
