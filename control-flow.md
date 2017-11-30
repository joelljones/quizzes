# Quiz: Control Flow

1. How would you properly refactor this code using the ternary operator?

  ```javascript
  if (walkSignal === 'Walk') {
      console.log('Walk!');
  } else {   
      console.log('Do Not Walk!');
  }
  ```

  - [ ] `walkSignal ? console.log('Walk!') : console.log('Do Not Walk!');`
  - [x] `walkSignal === 'Walk' ? console.log('Walk!') : console.log('Do Not Walk!');`
  - [ ] `walkSignal === 'Walk' : console.log('Walk!') ? console.log('Do Not Walk!');`
  - [ ] `walkSignal === 'Walk' ? ('Walk!') : ('Do Not Walk!');`

1. What is the operator for "greater than or equal to"?

  - [x] `>=`
  - [ ] `=>`
  - [ ] `>`
  - [ ] `>==`

1. What is the logical operator for "both of these things must be true" ?

  - [ ] `||`
  - [x] `&&`
  - [ ] `!`

1. What will the following code log to the console?

  ```javascript
  let weather = "spring";
  let clothingChoice = "";

  if (weather === "spring") {
    clothingChoice = "You need a light jacket, and possibly an umbrella.";
  } else if (weather === "summer") {
    clothingChoice = "Make sure to take your sunscreen.";
  } else if (weather === "fall") {
    clothingChoice = "Wear a light jacket.";
  } else {
    clothingChoice = "Wear a heavy coat.";
  }
  console.log(clothingChoice);
  ```

  - [ ] Wear a light jacket.
  - [ ] Make sure to take your sunscreen.
  - [ ] Wear a heavy coat.
  - [x] You need a light jacket, and possibly an umbrella.

1. Which of the following blocks of code will execute?

  ```javascript
  let isHungry = false;
  let moneyInPocket = 14;

  if (isHungry && moneyInPocket > 10) {
    console.log("Let's go out for lunch!");
  } else if (!isHungry && moneyInPocket > 10) {
    console.log("Save that money for later!");
  } else if (isHungry && moneyInPocket < 10) {
    console.log('Eat something at home');
  } else {
    console.log('Save up for when you are hungry!');
  }
  ```

  - [ ] `console.log('Save up for when you are hungry!');`
  - [x] `console.log("Save that money for later!");`
  - [ ] `console.log('Eat something at home!');`
  - [ ] `console.log("Let's go out for lunch!");`

1. What will the following code log to the console?

  ```javascript
  let runTime = 35;
  let runDistance = 3.5;
  if (runTime <= 30 && runDistance > 3.5) {
    console.log("You're super fast!");
  } else if (runTime >= 30 && runDistance <=3) {
    console.log("You're not making your pace!");
  } else if (runTime > 30 || runDistance > 3) {
    console.log('Nice workout!');
  } else {
    console.log('Keep on running!');
  }
  ```

  - [ ] You're super fast!
  - [ ] Keep on running!
  - [x] Nice workout!
  - [ ] You're not making your pace!

1. Which of the following variables contains a truthy value?

  - [ ] `let varThree = 0;`
  - [ ] `let varFour = '';`
  - [x] `let varOne = "false";`
  - [ ] `let varTwo = false;`

1. What will the following code log to the console?

  ```javascript
  let needTacos = true;

  if (needTacos) {
      console.log("Finding tacos");
  } else {
      console.log("Keep on keeping on!");
  }
  ```

  - [ ] Keep on keeping on!
  - [x] Finding tacos

1. What will the following code log to the console?

  ```javascript
  let groceryItem = "apple";

  switch (groceryItem) {
    case "tomato":
      console.log("Tomatoes are $0.49");
      break;
    case "lime":
      console.log("Limes are $1.49");
      break;
    case "papaya":
      console.log("Papayas are $1.29");
      break;
    default:
      console.log("Invalid item");
      break;
  }
  ```

  - [ ] Limes are $1.49
  - [ ] Papayas are $1.29
  - [ ] Tomatoes are $0.49
  - [x] Invalid item

1. Which of the following operators checks if two variables are equal?

  - [ ] `==`
  - [ ] `=`
  - [x] `===`
