# Quiz: Sizing Elements

1. The code below will display images in which of the following ways?

  ```css
  .container {
    width: 50%;
    height: 200px;
    overflow: hidden;
  }

  .container img {
    max-width: 100%;
    height: auto;
    display: block;
  }
  ```

  - [x] Images will shrink to the full width of their container, scale proportionally, and display partially if the image dimensions exceed container dimensions.
  - [ ] Images will span half of width of their container, scale proportionally, and display partially if the image dimensions exceed container dimensions.
  - [ ] Images will span half of the width of their container, scale proportionally, and display entirely.
  - [ ] Images will shrink to the full width of their container, scale unproportionally, but display entirely.

1. Which of the following is the root element that rems size relative to?

  - [x] `<html>`
  - [ ] `<head>`
  - [ ] `<root>`
  - [ ] `<body>`

1. What is the difference between an em and a rem?

  - [ ] A rem sizes using pixels, whereas ems size using percentages.
  - [ ] An em sizes relative to the root element, whereas rems size relative to a parent element's base font.
  - [ ] An em sizes using pixels, whereas rems size using percentages.
  - [x] An em sizes relative to a parent element's base font, whereas rems size relative to the root element's font size.

1. What are the minimum dimensions of a div with the following properties?

  ```css
  div.container {
    min-height: 150px;
    max-height: 600px;
    min-width: 300px;
    max-width: 900px;
  }
  ```

  - [ ] 600 pixels wide and 900 pixels tall.
  - [ ] 150 pixels wide and 300 pixels tall.
  - [x] 150 pixels tall and 300 pixels wide.
  - [ ] 600 pixels tall and 900 pixels wide.

1. When percentages are used to size padding and width, dimensions are set relative to which of the following?

  - [ ] The height of the child element.
  - [ ] The width of the child element.
  - [x] The width of the parent element.
  - [ ] The height of the parent element.

1. Assume the default font size of a browser is 12 pixels. The following code will size the paragraph's text to how many pixels?

  ```css
  p {
    font-size: 1.5em;
  }
  ```

  - [ ] 16 pixels
  - [ ] 12 pixels
  - [ ] 14 pixels
  - [x] 18 pixels

1. Which of the following property/value pairs will ensure that the background image of the div in the code below will scale proportionally?

  ```css
  div {
    background-image: url('#');
    background-repeat: no-repeat;
    background-position: center;
    /* ? */
  }
  ```

  - [ ] `background-size: contain;`
  - [ ] `background-scale: cover;`
  - [ ] `background-scale: contain;`
  - [x] `background-size: cover;`

1. What is needed to change the default font size of the root element?

  - [ ] A CSS rule that targets the `font-family` of the `<root>` element.
  - [ ] A CSS rule that targets the `font-size` of the `<root>` element.
  - [ ] A CSS rule that targets the `font-family` of the `<html>` element.
  - [x] A CSS rule that targets the `font-size` of the `<html>` element.

1. In the code below, how many pixels should the font size of the root element be set to in order to set the size of main headings to 36 pixels?

  ```css
  html {
    font-size: ?
  }

  h1 {
    font-size: 2rem;
  }
  ```

  - [ ] 16 pixels
  - [x] 18 pixels
  - [ ] 14 pixels
  - [ ] 12 pixels

1. Which of the following is an advantage of using relative units of measurements over hard-coded measurements?

  - [x] Relative units of measurements ensure consistent proportions across a website, regardless of screen size or layout.
  - [ ] Relative units better communicate the intent of a layout.
  - [ ] Relative units offer no significant advantages over hard-coded measurements.
  - [ ] Relative units allow the browser to render the web page faster.

1. What are the maximum dimensions of a div with the following properties?

  ```css
  div.container {
    min-height: 150px;
    max-height: 600px;
    min-width: 300px;
    max-width: 900px;
  }
  ```

  - [x] 600 pixels tall and 900 pixels wide.
  - [ ] 150 pixels tall and 300 pixels wide.
  - [ ] 150 pixels wide and 300 pixels tall.
  - [ ] 600 pixels wide and 900 pixels tall.

1. An em represents which of the following?

  - [ ] The width of a capital letter M in the base font being used.
  - [ ] The size of the root element's font.
  - [x] The size of the base font in use.
  - [ ] The height of a capital letter M in the base font being used.

1. The following code will set the paragraph's text to how many pixels?

  ```css
  html {
    font-size: 16px;
  }

  .splash-section {
    font-size: 18px;
  }

  .splash-section p {
    font-size: 1.5rem;
  }
  ```

  - [ ] 27 pixels
  - [x] 24 pixels
  - [ ] 18 pixels
  - [ ] 16 pixels

1. The "height" property in the code below should be set to which of the following values to ensure that the image remains proportional to its original size?

  ```css
  img {
    width: 500px;
    height: ?
  }
  ```

  - [ ] `custom`
  - [ ] `set`
  - [x] `auto`
  - [ ] `remain`

1. The following code will size all h1 elements in "splash-section" to how many pixels?

  ```css
  html {
    font-size: 12px;
  }

  .splash-section {
    font-size: 16px;
  }

  .splash-section h1 {
    font-size: 1.5em;
  }
  ```

  - [ ] 16 pixels
  - [x] 24 pixels
  - [ ] 12 pixels
  - [ ] 20 pixels

1. When percentages are used to size height and width, dimensions are set relative to which of the following?

  - [x] The parent of a child element.
  - [ ] The root element.
  - [ ] The child of a parent element.
  - [ ] The sub-child of a child element.
