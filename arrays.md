# Quiz: Arrays

1. What is the purpose of an array?

  - [ ] To organize data at lettered positions.
  - [x] To organize data as a list.
  - [ ] To organize data into key/value pairs.

1. What will happen after running the following code?

  ```javascript
  const countries = ['Japan', 'Denmark', 'Mexico', 'Morocco'];
  countries.shift();
  console.log(countries);
  countries =  ['England', 'Mozambique', 'Cambodia', 'Peru'];
  console.log(countries);
  ```

  - [x] One array will be logged to the console followed by an error message: `['Denmark', 'Mexico', 'Morocco']; TypeError: Assignment to constant variable`
  - [ ] Two arrays will be logged to the console: `['Denmark', 'Mexico', 'Morocco']; ['England', 'Mozambique', 'Cambodia', 'Peru'];`
  - [ ] One array will be logged to the console followed by an error message: `['Japan', 'Denmark', 'Mexico']; TypeError: Assignment to constant variable`
  - [ ] Two arrays will be logged to the console: `['Japan', 'Denmark', 'Mexico']; ['England', 'Mozambique', 'Cambodia', 'Peru'];`

1. What is the correct syntax for an array?

  - [ ] `let myArray = {'Rappel into a cave', 'Take a falconry class', 'Learn to juggle'};`
  - [ ] `let myArray = 'Rappel into a cave', 'Take a falconry class', 'Learn to juggle';`
  - [x] `let myArray = ['Rappel into a cave', 'Take a falconry class', 'Learn to juggle'];`
  - [ ] `let myArray = ['Rappel into a cave'; 'Take a falconry class'; 'Learn to juggle'];`

1. What will be logged to the console when we run the code below?

  ```javascript
  let myArray = ['item 0', 'item 1', 'item 2'];

  myArray.push('item 3');
  myArray.pop();

  console.log(myArray);
  ```

  - [ ] `['item 1', 'item 2', 'item 3']`
  - [ ] `['item 0', 'item 1', 'item 2', 'item 3']`
  - [x] `['item 0', 'item 1', 'item 2']`

1. Which of the methods below does _not_ change the array it is called on?

  - [ ] `.pop()`
  - [ ] `.shift()`
  - [ ] `.push()`
  - [x] `.slice()`

1. How could you access the second item, 'Lion', in the code below?

  ```javascript
  let animalArray = ['Sloth', 'Lion', 'Chipmunk'];
  ```

  - [ ] `animalArray[2]`
  - [ ] `animalArray['Lion']`
  - [x] `animalArray[1]`

1. What is the result of the following code?

  ```javascript
  const fruits = ['Apples', 'Oranges', 'Pears', 'Mangos'];
  fruits[2] = 'Bananas';
  console.log(fruits);
  ```

  - [ ] ['Apples', 'Oranges', 'Pears', 'Bananas', 'Mangos']
  - [ ] ['Apples', 'Bananas', 'Pears', 'Mangos']
  - [ ] ['Apples', 'Oranges', 'Bananas', 'Pears', 'Mangos']
  - [x] ['Apples', 'Oranges', 'Bananas', 'Mangos']

1. What will be logged to the console when we run the code below?

  ```javascript
  let cities = ['Chicago', 'San Fransisco', 'New York'];

  console.log(cities[3]);
  ```

  - [ ] Chicago
  - [x] undefined
  - [ ] New York

1. What will the errands array contain after we execute the code below?

  ```javascript
  let errands = ['Go to the bank', 'Pick up dry cleaning', 'Go grocery shopping'];

  errands.shift();
  ```

  - [ ] ['Pick up dry cleaning', 'Go grocery shopping', 'Go to the bank'];
  - [x] ['Pick up dry cleaning', 'Go grocery shopping'];
  - [ ] ['Go grocery shopping', 'Go to the bank', 'Pick up dry cleaning'];
  - [ ] ['Go to the bank', 'Pick up dry cleaning'];

1. How can you find how many items are within an array?

  - [x] `myArray.length`
  - [ ] `myArray.findLength`
  - [ ] `length(myArray)`
