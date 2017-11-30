# Quiz: Loops

1. What will be the result of the code below?

  ```javascript
  let animals = ['Grizzly bear', 'Sloth', 'Sea lion'];

  for (let animalsIndex = 0; animalsIndex < animals.length; animalsIndex++) {
  	console.log(animals[animalsIndex]);
  }
  ```

  - [ ] 'Sea Lion', 'Grizzly Bear', 'Sloth'
  - [x] 'Grizzly Bear', 'Sloth', 'Sea Lion'
  - [ ] '0: Grizzly Bear', '1: Sloth', '1: Sea Lion'
  - [ ] animals[0], animals[1], animals[2]

1. What is the stop condition of this loop?

```javascript
or (let i = 0; i < 10; i++) {
	console.log('Loop: ' + i);
}
```

  - [x] `i < 10`
  - [ ] `let i = 0`
  - [ ] `console.log('Loop: ' + i);`
  - [ ] `i++`

1. What is a good use for nested `for` loops?

  - [ ] Nested loops are bad - they run forever.
  - [ ] Nested loops run the same code twice.
  - [x] To compare two lists.
  - [ ] Nested loops allow us to double check our `if`/`else` statements.

1. What is incorrect about the code below?

  ```javascript
  for (let i = 0, i < myArray.length,  i++) {
    console.log(myArray[i]);
  }

  ```

  - [ ] The incrementer should be `i+=1`.
  - [x] The loop's conditions should be separated by semicolons instead of commas.
  - [ ] `let` is not needed for the start condition.
  - [ ] `i++` should be `i = i + 1`.

1. What problem is caused by the code below?

  ```javascript
  for (let i = 10; i > 0; i++) {
    console.log(i);
  }
  ```

  - [x] The code will loop forever because the start condition is `i = 10`, the stop condition is `i > 0`, and we are adding to `i` rather than subtracting. The iterator condition should be `i--`.
  - [ ] The code won't run because the stop condition is less than the start condition.
  - [ ] You can't run a loop without an array.
  - [ ] `i = 10` and `i > 0` should be switched.

1. Which statement is true about `while` loops?

  - [ ] `while` loops always loop over a code block a known amount of times.
  - [ ] `while` loops will run at least once, then will run again if their condition is true.
  - [x] `while` loops run an infinite amount of times as long as their condition remains true.
  - [ ] `while` loops only run while their condition is false.

1. Which statement is true about `for` loops?

  - [ ] `for` loops never result in infinite loops because their stop condition is set from the beginning.
  - [ ] `for` loops always count from `0` upwards.
  - [ ] `for` loops run an unknown amount of times.
  - [x] `for` loops always loop over a code block a known amount of times.
