# Quiz: HTML, CSS and Git

__1. Why do merge conflicts happen?__

  - [x] When two branches with updates to the same line in a file are merged.

  - [ ] When two branches with updates to the same file are merged.

  - [ ] Staging a file.

  - [ ] Creating a new branch.

  __EXPLANATION__

  When merging 2 branches that contain changes to the same line in a file, git doesn't know which change is the correct. A merge conflict occurs to allow developers to adjust code to the correct state.

  ---

__2. What are/is an advantage of using git branches?__

  - [ ] Able to work on multiple features at the same time.

  - [ ] Able to work on big features without affecting the state of the master branch.

  - [ ] Easy to keep track of all changes made compared to the master branch before merging.

  - [x] All of the above.

  __EXPLANATION__

  When creating a new branch for every feature you are working on, the commits made on a specific branch will only update the content in that branch. This means the state of other feature branches will not be affected. When working on a big feature you should commit small finished changes often. These commits will not affect the master branch. This means that you can make a lot of small changes on your branch and merge to master when the whole feature is finished. When you finish working on a feature you can use the git diff master command to review your changes before merging.

  ---

__3. What does the__ -a __switch in__ git commit __do?__

  - [ ] Resets the author of the change to the specified user.

  - [ ] Allows an empty commit message.

  - [x] Stages all file modifications and deletions.

  - [ ] Amends the previous commit with the new modifications, instead of making a new one.

  __INTERVIEW QUESTION__

  This is a real question that is commonly asked in engineering interviews.

  -a tells git commit to automatically stage files that have been modified and deleted. (New files are not affected.)

  ---

__4. How would you use CSS to make all of the `<p>` elements on your webpage have a font color of blue?__

  - [x]
  ```
    p {
        color: blue;
    }
  ```

  - [ ]
  ```
  p {
      font-color: blue;
  }
  ```

  - [ ]
  ```
  paragraph {
      color: blue
  }
  ```

  - [ ]
  ```
  all(p) {
      letter-color: blue;
  }
  ```

  __EXPLANATION__

  This question asks you to use a selector for the `<p>` tag. To do this, specify the tag name without the brackets and use open and close braces to organize the style properties you want associated with that tag. The property that dictates the font color is the color property.

  ---

__5. Which command creates a new repo?__

  - [ ] git clone

  - [x] git init

  - [ ] git add

  - [ ] git new

  __EXPLANATION__

  git init creates an empty Git repository or reinitialize an existing one. git clone clones an existing repo. git add adds file contents to the index. git new is not a valid git command.

  ---

__6. Which one of these would we use in our HTML page in order to specify a file (style.css) to use for our page style?__

  - [ ] `<link ref='style.css'></link>`

  - [ ] `<link href='style.css'>`

  - [x] `<link rel='stylesheet' href='style.css'>`

  - [ ] `<style type='css' rel='stylesheet' href='style.css'>`

  __INTERVIEW QUESTION__

  This is a real question that is commonly asked in engineering interviews.

  The `<link>` element is the correct tag to specify stylesheets to use with your your page. The type attribute lets the browser know what kind of media file it is, the `rel` attribute specifies the relationship between the linked document and your page while the href attribute lets the browser know where to find the file.

  ---

__7. Which option shows correct usage of the HTML paragraph tag?__

  - [ ] `<paragraph>I lived with them on Montague Street, in a basement down the stairs</paragraph>`

  - [ ] `paragraph {I lived with them on Montague Street, in a basement down the stairs }`

  - [x] `<p>I lived with them on Montague Street, in a basement down the stairs</p>`

  - [ ] `<!--p I lived with them on Montague Street, in a basement down the stairs -->`

  __EXPLANATION__

  The HTML tag for paragraph text is `<p>`.

  ---

__8. Which heading tag defines the most important text?__

  - [x] `<h1>Welcome to my site!</h1>`

  - [ ] `<h6>Welcome to my site!</h6>`

  - [ ] `<title>Welcome to my site!</title>`

  - [ ] `<header>Welcome to my site!</header>`

  __EXPLANATION__

  HTML heading tags are `<h1>` through `<h6>`. `<h1>` defines the most important heading. `<h6>` defines the least important heading.

  The `<header>` element is a container for introductory content or a set of navigational links, and typically contains one or more heading elements (`<h1>` through `<h6>`), a logo or icon, and authorship information.

  ---

__9. Which of the following `<img>` tags uses an "absolute" URL?__

  - [x] `<img src='http://www.aol.com/images/logo.png'>`

  - [ ] `<img src='/images/logo.png'>`

  - [ ] `<img src='images/logo.png'>`

  - [ ] `<img src='logo.png'>`

  __INTERVIEW QUESTION__

  This is a real question that is commonly asked in engineering interviews.

  An absolute URL contains a protocol (like http), a domain (like www.aol.com), and a path (like /images/logo.png). Without all three of these items, a URL is "relative", not "absolute".

  ---

__10. Which of these HTML tags represents the header cell of an HTML table?__

  - [ ] `<table>`

  - [ ] `<tr>`

  - [x] `<th>`

  - [ ] `<td>`

  __EXPLANATION__

  `<table>` surrounds an entire table. `<tr>` surrounds a whole row, not just a header cell. `<td>` surrounds a standard cell, not a header cell. `<th>` is the correct answer.

  ---

__11. What does this HTML do?__

`<a href='http://www.example.com'>Example Website</a>`

  - [ ] Imports a CSS stylesheet from example.com

  - [x] Links "Example Website" to example.com

  - [ ] Creates a form that, when submitted, sends data to example.com

  - [ ] Embeds AngularJS from example.com

  __EXPLANATION__

  The `<a>` tag creates a hyperlink that links one page to another.

  ---

__12. What statement is true for the following CSS code?__

```
p {
  color: hotpink;
  text-align: center;
}
```

  - [ ] `p` is a selector, `color` and `text-align` are values, and `hotpink` and `center` are properties

  - [ ] `p` is a property, c`olor` and `text-align` are selectors, and `hotpink` and `center` are values

  - [x] `p` is a selector, `color` and `text-align` are properties, and `hotpink` and `center` are values

  - [ ] None of the above

  __EXPLANATION__

  `color: hotpink` and `text-align: center` are "rules", which are property/value pairs. `p` is a selector.

  ---

__13. Which choice best describes how you should typically use a class selector vs. an ID selector?__

  - [ ] ID selectors are only for important messages, so typically just use class

  - [ ] Use ID selectors for colors and typography, and class selectors for images and other formatting

  - [ ] Use ID selectors to target a type of element (like `img` or `h1`), and class selectors to get more specific

  - [x] Use class selectors if you'll reuse the style on more than one element, and ID selectors to target a single element on the page

  __EXPLANATION__

  Class selectors, preceded by a period (.), define styles that you can apply to any element, regardless of type. ID Selectors, preceded by a hash (#), target a single element on the page.

  ---

__14. Which of these colors has the most red?__

  - [ ] #909090

  - [x] #ff0000

  - [ ] #005eff

  - [ ] #141572

  __EXPLANATION__

  The first two characters of a hexadecimal color represent red. Since f is the highest hexadecimal digit, `#ff0000` has the most red. `#005eff`, by comparison, has the least red, but the most blue.
