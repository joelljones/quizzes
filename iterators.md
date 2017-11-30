# Quiz: Iterators

1. Which of the following methods returns a boolean value?

  - [ ] `.forEach()`
  - [x] `.some()`
  - [ ] `.map()`
  - [ ] `.filter()`

1. Which of the following methods returns an array with values that evaluate to truthy based on the condition in the method's block?

  - [ ] `.map()`
  - [x] `.filter()`
  - [ ] `.some()`
  - [ ] `.forEach()`

1. Which of the following methods returns a new array?

  - [ ] `.every()`
  - [ ] `.forEach()`
  - [x] `.filter()`
  - [ ] `.some()`

1. What will the following code return?

  ```javascript
  let animals = ['bears', 'cats', 'dogs', 'elephants', 'giraffes'];

  animals.every(animal => animal.length < 5);
  ```

  - [ ] `null`
  - [x] `false`
  - [ ] `true`
  - [ ] `undefined`

1. What is the correct way to refactor the code below to use arrow function syntax?

  ```javascript
  namesArray.forEach(function(name) {
    console.log('Welcome, ' + name + '!');
  }
  ```

  A.
  ```javascript
  namesArray.forEach(name =>  console.log('Welcome, ' + name + '!'));
  ```

  B.
  ```javascript
  namesArray.forEach => console.log('Welcome, ' + name + '!');
  ```

  C.
  ```javascript
  namesArray.forEach(function => name {
    console.log('Welcome, ' + name + '!');
  }
  ```

  D.
  ```javascript
  namesArray.forEach( => console.log('Welcome, ' + name + '!'));
  ```

  - [x] A
  - [ ] B
  - [ ] C
  - [ ] D

1. What will the following code return?

  ```javascript
  let animals = ['bears', 'cats', 'dogs', 'elephants', 'giraffes'];

  animals.some(animal => animal.length < 5);
  ```

  - [ ] `false`
  - [x] `true`
  - [ ] `['cats', 'dogs']`

1. Which of the following iterator methods returns `undefined`?

  - [ ] `.filter()`
  - [ ] `.map()`
  - [x] `.forEach()`
  - [ ] `.some()`
