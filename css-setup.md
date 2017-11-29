# Quiz: CSS Setup

1. CSS code can be written in an HTML file with which of the following tags?

  - [ ] `<stylesheet>`
  - [x] `<style>`
  - [ ] `<CSS>`
  - [ ] `<css>`

1. A stylesheet will not style any HTML code unless which of the following occurs?

  - [ ] The stylesheet contains a CSS document type declaration.
  - [ ] The stylesheet is named using the required `style.css` filename.
  - [ ] The stylesheet ends with __.style__ as the file extension.
  - [x] The stylesheet is linked to the HTML page using a `<link>` tag.

1. The following HTML code attempts to use inline styling to change the color of the paragraph text, but fails to do so. Why?

  ```html
  <p color="red;">I'm learning to code!</p>
  ```

  - [ ] The color `red` should be set to `Red` instead.
  - [ ] The `color` attribute must be changed to `color-style`.
  - [x] The `color` attribute is invalid. It should be changed to `style` and then set equal to `color: red;`.
  - [ ] The value of the `color` attribute must be changed to `style: red;`.

1. Separating HTML and CSS into their own files helps accomplish which of the following?

  - [x] Separating HTML structure from CSS style to make code easier to read and reuse.
  - [ ] A better experience for users that visit your web page.
  - [ ] An approval rating of 'A' from the W3C for your code.
  - [ ] Faster loading times for web pages by browsers.

1. The following code attempts to style a paragraph using the `<style>` tag, but fails to do so. Why?

  ```html
  <head>
    <style>
      <p style="color:red;">I'm learning to code!</p>
    </style>
  </head>
  ```

  - [ ] The value of the `color` attribute must be changed to` style:red;`.
  - [ ] The `color` attribute must be changed to `color-style`.
  - [x] The contents of the `<style>` tag must be CSS code, not HTML code.
  - [ ] The `style` attribute of the `<p>` element can be removed because the `<style>` tag replaces it.

1. You wish to link a CSS file called __main.css__ to an HTML file. Which of the following lines of code correctly links the HTML file and the stylesheet?

  - [ ] `<link href="main.css" type="css/text" rel="stylesheet" />`
  - [ ] `<link href="main.css" type="stylesheet" rel="css/text" />`
  - [ ] `<link href="main.css" type="stylesheet" rel="text/css" />`
  - [x] `<link href="main.css" type="text/css" rel="stylesheet" />`

1. Using a `<style>` tag for CSS code instead of inline styles helps accomplish which of the following?

  - [ ] A decrease in the amount of time the browser needs to render a web page.
  - [ ] A better experience for users that visit your web page.
  - [x] A clear separation between a structural language (HTML) and a styling language (CSS).
  - [ ] There are no significant advantages to using a `<style>` tag over inline styles.

1. What is the main difference between inline styles and the `<style>` tag?

  - [ ] Inline styles allow you to write CSS in a separate file, whereas the `<style>` tag embeds CSS directly within HTML opening tags.
  - [ ] There is no difference between inline styles and the `<style>` tag.
  - [ ] The `<style>` tag allow you to write CSS in a separate file, whereas inline styles embed CSS directly within HTML opening tags.
  - [x] Inline styles directly modify HTML elements using a `style` attribute, whereas the `<style>` tag allows you to write CSS in a dedicated section of the HTML file.
