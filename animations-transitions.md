# Quiz: Animations - Transitions

1. Which best describes the use of a comma (,) in the transition syntax?

  - [ ] The comma is used to reverse the flow of the transition.
  - [ ] The comma is used to replace the colon; it looks nicer.
  - [x] The comma is used to animate multiple properties in one statement.
  - [ ] The comma is used to animate one property with different durations.

1. Which of the following transition timing function values will cause the value to change at a constant speed?

  - [x] `linear`
  - [ ] `ease`
  - [ ] `ease-in`
  - [ ] `ease-in-out`

1. Which is the preferred order of the values in the transition shorthand syntax?

  - [ ] Property, duration, delay, timing function.
  - [ ] Property, timing function, delay, duration.
  - [ ] Duration, timing function, property, delay.
  - [x] Property, duration, timing function, delay.

1. Which best describes the effect of the following CSS rule?

  ```css
  a {
    transition-property: color;
    transition-duration: 2s;
    transition-delay: 1s;
  }
  ```

  - [ ] When the link first appears, it will blend over two seconds, after a one second pause.
  - [ ] When the links text color changes, it will blend over one second, after a two second pause.
  - [ ] When the link's background color changes, it will blend over two seconds, after a one second pause.
  - [x] When the link's text color changes, it will blend over two seconds, after a one second pause.

1. Which of the following is NOT valid syntax for the CSS rule transition?

  - [ ] `transition: ease-in color 100ms;`
  - [ ] `transition: color 1.5s 100ms ease-in;`
  - [x] `transition: 1.5s 10s 20s;`
  - [ ] `transition: color 1.5s ease-in 100ms;`

1. Which CSS transition property can be given a value of all?

  - [x] `transition-property`
  - [ ] `transition-duration`
  - [ ] `transition-delay`
  - [ ] `transition-timing-function`

1. Which of the following is a valid value for transition-duration?

  - [x] `750ms`
  - [ ] `220px`
  - [ ] `ease-out`
  - [ ] `300%`

1. Which of the following is a valid transition-timing-function value?

  - [x] `ease-in`
  - [ ] `transition`
  - [ ] `bounce`
  - [ ] `soft-out`

1. Which of the following CSS properties can NOT be transitioned?

  - [ ] `height`
  - [x] `background-image`
  - [ ] `width`
  - [ ] `color`

1. Which of the following is NOT a valid CSS transition property?

  - [ ] `transition-duration`
  - [ ] `transition-timing-function`
  - [x] `transition-pause`
  - [ ] `transition-delay`

1. What is the default value of transition-duration?

  - [ ] `100s`, by default transitions take 100 seconds
  - [ ] `1s`, by default transitions take one second
  - [ ] `750ms`, by default transitions take 3/4 of a second
  - [x] `0s`, by default transitions happen instantly

1. Which best describes the effect of the following CSS rule?

  ```css
  a {
    transition-property: color;
    transition-delay: 1s;
  }
  ```

  - [ ] When a link is hovered over, the browser will freeze for one second
  - [ ] When a link is clicked, it will first pause for one second before loading the URL in the link's `href` attribute
  - [x] When a link changes text color, it will first pause for one second
  - [ ] When a link changes color, it will blend smoothly over one second
