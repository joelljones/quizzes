# Quiz: HTML & CSS

__1. Choose the correct HTML element for the most important heading on a page:__

  - [ ] `<head>`
  - [ ] `<headings>`
  - [x] `<h1>`
  - [ ] `<h6>`

  ---

__2. To select all paragraph elements that have the class name "key", the selector would be:__

  - [x] p.key
  - [ ] key.p
  - [ ] key p
  - [ ] .p key

  ---

__3. What tag is used to create a table cell inside of a table row?__

  - [x] `<td>`

  - [ ] `<tr>`

  - [ ] `<th>`

  - [ ] `<tc>`

  __EXPLANATION__

  The `<tr>` element defines a table row, the `<th>` element defines a table header, and the `<td>` element defines a table cell. `<tc>` is not a valid table element.

  ---

__4. The CSS selector pattern `element element` is known as what type of selector? For example: `.navbar .logo` or `div p`__

  - [ ] `child selector`
  - [ ] `sibling selector`
  - [ ] `ancestor selector`
  - [x] `descendent selector`

  ---

__5. In `<img src='w3schools.jpg' width='104' height='142'>`, how many attributes are there?__

  - [ ] 1

  - [ ] 2

  - [x] 3

  - [ ] 4

  __EXPLANATION__

  HTML attributes provide additional information about an element. They are are always specified in the start tag and come in name/value pairs like: name=’value’.

  ---

__6. In order to render CSS properly on a mobile device, what do you need to include in your header?__

  - [x] `<meta name='viewport' content='width=device-width, initial-scale=1'>`
  - [ ] `<viewport content='width=device-width, initial-scale=1'>`
  - [ ]
  ```
  *, *::before, *::after {
      min-width: 640px;
  }
  ```

  - [ ]
  ```
  @media (min-width: 640px) {
     /* Style information will go here */
   }
   ```

  __EXPLANATION__

  The viewport `meta` tag is an HTML tag that indicates how the browser should render the content of the page in a device's viewport. The viewport is a virtual window, like a browser window, that contains the display of the browser's content. Since the viewport tag is a `<meta>` tag, it belongs inside the `<head>` tag.

  ---

__7. What should you do to organize your CSS in a way that is easier to maintain across a single application?__

  - [ ] Include CSS in the <head> tag of your HTML file.

  - [ ] Minify your CSS.

  - [x] Use separate CSS files for different parts of the application.

  - [ ] Combine your CSS into one file.

  __EXPLANATION__

  Using separate files for your CSS keeps it readable if it ever needs to be changed.

  ---

__8. Select the correct basic HTML document structure.__

  - [ ]
  ```
  <!DOCTYPE html>
  <html>
    <body>
      <head>
        <title>Title of the document</title>
      </head>
      The content of the document...
    </body>
  </html>
  ```

  - [x]
  ```
  <!DOCTYPE html>
  <html>
    <head>
      <title>Title of the document</title>
    </head>
    <body>
      The content of the document...
    </body>
  </html>
  ```

  - [ ]
  ```
  <!DOCTYPE html>
  <html>
    <body>
      The content of the document...
    </body>
    <head>
      <title>Title of the document</title>
    </head>
  </html>
  ```

  - [ ]
  ```
  <!DOCTYPE html>
  <html>
    <head>
      <title>Title of the document</title>
      <body>
        The content of the document...
      </body>
    </head>
  </html>
  ```

  __EXPLANATION__

  The `<!DOCTYPE>` declaration must be the very first thing in your HTML document, before the `<html>` tag. The `<title>` tag is included in the `<head>`. The `<head>` element is included before the `<body>`.

  ---

__9. What is the default value for the CSS property vertical-align?__

  - [ ] top

  - [ ] middle

  - [x] baseline

  - [ ] bottom

  __EXPLANATION__

  `vertical-align` orients inline or table-cell content vertically. The middle value centers our nav links vertically within their containers. The default value is `baseline`, which aligns the baseline of the element with the baseline of the parent element.

  ---

__10. In CSS, the asterisk symbol `(*)` is known as the ___ __selector.__

  - [x] universal or wildcard

  - [ ] compass

  - [ ] ambiguous

  - [ ] catch-all

  __EXPLANATION__

  The universal `(*)` selector matches any element type and selects all elements.

  When * is used as a wildcard, it is called the CSS Attribute Selector.
