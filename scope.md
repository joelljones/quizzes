# Quiz: Scope

1. Which best defines a variable with block scope?

  - [x] A variable that is defined within a block and only available inside a block.
  - [ ] A variable that is available outside of a block.
  - [ ] A variable that is available throughout a program.
  - [ ] A variable that is available within a function.

1. What will be the output of this code?

  ```javascript
  let sayHello = 'Hi there';
  const sayGoodbye = 'Goodbye';

  const speakItalian = () => {
    sayHello = 'Ciao!';
    console.log(sayHello);
    console.log(sayGoodbye);
  }

  speakItalian();
  ```

  - [ ] Ciao!  ReferenceError: variable not defined.
  - [ ] Hi there  Goodbye
  - [x] Ciao!  Goodbye

1. What is a globally scoped variable?

  - [ ] A variable that is accessible in a block, and only inside a block.
  - [ ] A variable that is defined in a function.
  - [ ] A variable that is also a parameter.
  - [x] A variable that is accessible to any part of the program.

1. What is preferable: defining variables in the global scope or defining variables in the block scope?

  - [ ] Defining variables in the global scope and the block scope are equally preferable.
  - [ ] Defining variables in the block scope. Variables defined at the block level can still be used at the global level.
  - [x] Defining variables in the block scope. Variables defined in the global scope can cause unexpected behavior in our code.
  - [ ] Defining variables in the global scope. Variables defined in the block scope are restrictive and often conflict with variables defined in the global scope.

1. Which variables possess block scope?

  ```javascript
  const input = prompt('Enter input value');
  const controlVal = input / 2 + 3;
  const multiplier = (number, phase) => {
    const val = number * controlVal + phase;
    console.log(val);
  };
  ```

  - [ ] `input`, `controlVal`, `multiplier`
  - [x] `number`, `phase`, `val`
  - [ ] `val`, `number`, `controlVal`, `phase`
  - [ ] `input`, `controlVal`

1. What will be the output of this code?

  ```javascript
  const roadTrip = () => {
    const destination = 'Crater Lake, Oregon';
    const snacks = ['jerky', 'chocolate covered almonds', 'water'];
    const supplies = ['tent', 'camp stove', 'sleeping bag'];
  }

  console.log('Next stop: ', destination);
  ```

  - [ ] Next stop: Crater Lake, Oregon
  - [x] Uncaught ReferenceError: destination is not defined
  - [ ] Next stop: destination

1. How many global variables are there in the following block of code?

  ```javascript
  const input = prompt('Enter input value');
  const controlVal = input / 2 + 3;
  const multiplier = (number, phase) => {
    const val = number * controlVal + phase;
    console.log(val);
  };
  ```

  - [ ] There are three: `input`, `controlVal`, and `val`.
  - [ ] There are two: `input` and `controlVal`.
  - [ ] There are four: `input`, `controlVal`, `val`, and `multiplier`.
  - [x] There are three: `input`, `controlVal`, and `multiplier`.
