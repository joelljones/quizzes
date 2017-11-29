# Quiz: Functions

1. Which of the following is a parameter in the block of code below?

  ```javascript
  let input = prompt('Enter input value');
  const controlVal = input / 2 + 3;
  const multiplier = (number, phase) => {
  	const val = number * controlVal + phase;
  	console.log(val);
  };
  ```

  - [ ] `val`
  - [ ] `input`
  - [x] `number`
  - [ ] `controlVal`

1. Which of the following demonstrates correct syntax for a function?

  - [ ] `const myFunction = {...}`
  - [x] `const myFunction = () => {...}`
  - [ ] `myFunction = () {...}`
  - [ ] `const myFunction{ () } (...)`

1. What will this code print to the console?

  ```javascript
  const workoutJournal = (miles, avgTime) => {
    console.log('I ran ' + miles + ' miles at an average of ' + avgTime + ' per mile.');
  }

  workoutJournal('3');
  ```

  - [ ] I ran 3 miles at an average of 7 minutes per mile.
  - [ ] I ran 3 miles at an average of per mile.
  - [ ] Uncaught ReferenceError: avgTime is not defined.
  - [x] I ran 3 miles at an average of undefined per mile.

1. How can you call this function?

  ```javascript
  const getCurrentDate = () => {
    let date = new Date();
    return date;
  }
  ```

  - [ ] `const getCurrentDate();`
  - [ ] `getCurrentDate(todaysDate);`
  - [ ] `getCurrentDate(){}`
  - [x] `getCurrentDate();`

1. What will this code print to the console?

  ```javascript
  const sleepTimer = (alarm) => {
    console.log('My alarm is set for: ' + alarm);
  }

  sleepTimer('8:30AM');
  ```

  - [ ] My alarm is set for: undefined
  - [ ] My alarm is set for: sleepTimer
  - [x] My alarm is set for: 8:30AM
  - [ ] My alarm is set for: alarm

1. Which of the following best describes what a function in JavaScript is used for?

  - [ ] A function allows for the use of mathematical operators.
  - [ ] A function is used for math formulas.
  - [ ] A function creates new variables.
  - [x] A function is a reusable piece of code that takes an input, operates on it, then returns an output.

1. What's the purpose of a parameter?

  - [x] To pass data to a function, which are then used when calling the function.
  - [ ] To prevent the function from being called without certain variables defined.
  - [ ] To make the data the function uses visible.

1. Which of the following most accurately describes the `volumeOfCube()` function?

  ```javascript
  let side = 5;

  function volumeOfCube () {
    side * side * side;
  }

  volumeCube();
  // Output: 125.
  ```

  - [x] It is a function declaration.
  - [ ] It is an arrow function.
  - [ ] It is an arrow function declaration.
  - [ ] It is a function expression.

1. Which of the following is the correct way to call the function below?

  ```javascript
  const multiplier = (number) => {
    console.log(3 * number);
  };
  ```

  - [ ] `multiplier{5}`
  - [x] `multiplier(5)`
  - [ ] `multiplier[5]`
  - [ ] `multiplier 5`

1. Which correctly represents the most condensed form of the function? Recall that this syntax is also known as 'concise body.'

  ```javascript
  const areaOfCircle = radius => { Math.PI * radius * radius };

  areaOfCircle(4);
  ```

  ```javascript
  const areaOfCircle = radius => return Math.PI * radius * radius;

  areaOfCircle(4);
  ```

  ```javascript
  const areaOfCircle = radius => { return Math.PI * radius * radius };

  areaOfCircle(4);
  ```

  ```javascript
  const areaOfCircle = radius => Math.PI * radius * radius;

  areaOfCircle(4);
  ```

  - [ ]
  - [ ]
  - [ ]
  - [x]
