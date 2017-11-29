# Quiz: Media Queries

1. What mistakes are present in the media query code below, if any?

  ```css
  @media only for screen and (max-width: 480px) {

  }
  ```

  - [ ] It is not necessary to define a media query only for `screen` devices.
  - [x] The `for` keyword is not needed.
  - [ ] There are no errors present in the code.
  - [ ] `max-width: 480px` should not be in parentheses.

1. Which of the following requirements must be met so that the media query below applies its corresponding CSS rules?

  ```css
  @media only screen and (max-width: 480px) and (min-resolution: 150dpi) {
    /* CSS rules */
  }
  ```

  - [ ] A browser with a width above 480px or a screen resolution below 150dpi.
  - [ ] A browser with a width below 480px or a screen resolution above 150dpi.
  - [ ] A browser with a width above 480px and a screen resolution below 150dpi.
  - [x] A browser with a width below 480px and a screen resolution above 150dpi.

1. At which dimensions should a media query breakpoint be added?

  - [x] It’s necessary to add breakpoints for dimensions where a website’s content naturally breaks or looks odd when resizing the browser.
  - [ ] It’s necessary to add breakpoints when the screen is 320px or thinner, or 480px or wider.
  - [ ] It’s necessary to add breakpoints for every device currently in use, so a website will appear correctly on every device.
  - [ ] It’s necessary to add a breakpoint about every 200px to make sure the page scales as it grows thinner or wider.

1. What is the purpose of a media query?

  - [ ] Media queries are the only way of adding media (images, videos, etc.) to CSS.
  - [x] Media queries allow websites to alter their CSS, often to resize and reorganize elements so that the website appears correctly on any device.
  - [ ] Media queries are exclusively for making websites mobile-friendly.
  - [ ] Media queries block a website from detecting what kind of device the site appears on.

1. What browser dimensions will meet the media query below?

  ```css
  @media only screen and (min-width: 200px) and (max-width: 600px) {

  }
  ```

  - [ ] A browser with a width of 1250px and a height of 625px.
  - [x] A browser with a width of 250px and a height of 750px.
  - [ ] A browser with a width of 620px and a height of 300px.
  - [ ] A browser with a width of 150px and a height of 450px.

1. What is a responsive website?

  - [ ] A website that responds to user input, like in the event of signing up for an email newsletter.
  - [ ] A website that shrinks its elements down, making the entire page visible on any device.
  - [ ] A website that alters its styles depending on the dimensions of the browser.
  - [ ] A website that appears only on one screen size.

1. Which of the following requirements must be met so that the media query below applies its corresponding CSS rules?

  ```css
  @media only screen and (min-width: 320px), (orientation: landscape) {
    /* CSS rules */
  }
  ```

  - [ ] A browser with a width below 320px or an orientation of portrait.
  - [x] A browser with a width above 320px or an orientation of landscape.
  - [ ] A browser with a width above 320px and an orientation of portrait.
  - [ ] A browser with a width below 320px and an orientation of landscape.
