# Quiz: Flexbox

1. Which of the following flex properties should be used to set all flex items to the same size before they shrink or grow to fill the flex container?

  - [ ] `flex-adjust`
  - [ ] `flex-shrink`
  - [x] `flex-basis`
  - [ ] `flex-container`

1. Which of the following display values will set an element to be a flex container and inline?

  - [ ] block-flex
  - [ ] flex
  - [ ] inline-block-flex
  - [x] inline-flex

1. Imagine there are 80 extra pixels along a major axis and elements #alpha, #beta, and #gamma have the following flex-grow values. How many extra pixels will element #alpha have?

  ```css
  #alpha {
    flex-grow: 2;
  }

  #beta {
    flex-grow: 1;
  }

  #gamma {
    flex-grow: 1;
  }
  ```

  - [ ] 20 pixels
  - [ ] 30 pixels
  - [x] 40 pixels
  - [ ] 10 pixels

1. Imagine there are 60 extra pixels along a major axis and elements #alpha, #beta, and #gamma have the following flex-grow values. How many extra pixels will element #alpha have?

  ```css
  #alpha {
    flex-grow: 2;
  }

  #beta {
    flex-grow: 3;
  }

  #gamma {
    flex-grow: 1;
  }
  ```

  - [ ] 40 pixels
  - [ ] 30 pixels
  - [x] 20 pixels
  - [ ] 10 pixels

1. Which of the following justify-content values positions all flex items in order with no added spacing at the end of the row?

  - [ ] flex-start
  - [ ] center
  - [x] flex-end
  - [ ] space-between

1. Which of the following is equivalent to the sample code below?

  ```css
  .item {
    flex-grow: 2;
    flex-shrink: 1;
    flex-basis: 120px;
  }
  ```

  - [ ] `flex: 1 2 1 2 120px`
  - [ ] `flex: 120px 1 2`
  - [x] `flex: 2 1 120px`
  - [ ] `flex: 1 2 120px`

1. Based on the code below, which of the following can we not assume?

  ```css
  div.headline {
    display: flex;
    flex-wrap: wrap;
    flex-shrink: 2;
  }
  ```

  - [ ] Divs of class `headline` will always shrink to fit their flex container.
  - [x] Container divs of class `headline` will have a vertical major axis.
  - [ ] Divs of class `headline` are flex containers and flex-children.
  - [ ] Direct children of divs of class `headline` will wrap to the next line if they do not fit in the container.

1. Which three values do the justify-content and align-items properties share?

  - [x] flex-start, flex-end, center
  - [ ] flex-start, baseline, flex-center
  - [ ] flex-start, baseline, stretch
  - [ ] flex-start, flex-end, flex-center

1. Which of the following properties is used to instruct the browser to wrap flex items that don't fit on one line?

  - [ ] wrap
  - [ ] flex
  - [ ] no-wrap
  - [x] flex-wrap

1. Imagine the flex items #alpha, #beta, and #gamma are each 50 pixels wide. How many pixels will separate each item if their flex container (.my-flex-container) has the following properties?

  ```css
  .my-flex-container {
    display: flex;
    width: 300px;
    justify-content: space-between;
  }
  ```

- [x] 75 pixels
- [ ] 25 pixels
- [ ] 100 pixels
- [ ] 50 pixels

1. Which of the following will set a flex container's flex-direction property to column and flex-wrap property to wrap?

  - [ ] `flex-flow: wrap column`
  - [ ] `flex: wrap column`
  - [x] `flex-flow: column wrap`
  - [ ] `flex: column wrap`

1. Which of the following justify-content values positions all flex items in order with no added spacing in the middle of the row?

  - [ ] flex-start
  - [ ] space-between
  - [x] center
  - [ ] flex-end

1. Imagine the flex items #alpha, #beta, and #gamma are each 100 pixels wide. How many pixels will separate the first flex item from the beginning of the row if its flex container has the following properties?

  ```css
  .flex-container {
    display: flex;
    width: 390px;
    justify-content: space-around;
  }
  ```

  - [x] 15 pixels
  - [ ] 25 pixels
  - [ ] 30 pixels
  - [ ] 50 pixels

1. What is the major axis of a flex container with flex-direction: column?

  - [x] vertical
  - [ ] horizontal
  - [ ] diagonal
  - [ ] center

1. Imagine the elements #alpha, #beta, and #gamma are 90 pixels too wide for their parent container. By how many pixels will element #alpha shrink if they each have the following flex-shrink values?

  ```css
  #alpha {
    flex-shrink: 2;
  }

  #beta {
    flex-shrink: 2;
  }

  #gamma {
    flex-shrink: 2;
  }
  ```

  - [ ] 10 pixels
  - [x] 30 pixels
  - [ ] 20 pixels
  - [ ] 40 pixels

1. Which of the following is a display value for a flexbox parent element?

  - [ ] absolute
  - [ ] static
  - [ ] relative
  - [x] flex
