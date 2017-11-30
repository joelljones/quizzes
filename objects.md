# Quiz: Objects

1. Which line of code will log the value saved to the `_num` key in the `tempObj` object.

  ```javascript
  let tempObj = {
    _num: 22,
    get num() {
      return this._num;
    }
  };
  ```

  - [ ] `console.log(tempObj.'_num');`
  - [x] `console.log(tempObj.num);`
  - [ ] `console.log(tempObj[num]);`
  - [ ] `console.log(tempObj.num());`

1. How can we add a property to the object below?

  ```javascript
  let bikes = {
    schwinn: 'blue',
    trek: 'black'
  }
  ```

  - [x] `bikes['specialized'] = 'red';`
  - [ ] `bikes.'specialized' = 'red';`
  - [ ] `let bikes.specialized = 'red'`
  - [ ] `bikes = specialized: 'red';`

1. What should we add to the empty `.withDiscount()` method to return the cost of the meatballs object with a two dollar discount?

  ```javascript
  let meatballs = {
    cost: 5,
    withDiscount() {

    }
  };
  ```

  - [ ] `cost - 2;`
  - [x] `return this.cost - 2;`
  - [ ] `this.cost - 2;`
  - [ ] `return cost - 2;`

1. Is there anything wrong with setter method in the example below? If so, what?

  ```javascript
  let tempObj = {
    _num: 22,
    set(numIn) {
      _num = numIn;
    }
  };
  ```

  - [ ] The setter input argument should be called `num`.
  - [x] The setter should contain `this._num` in place of `_num`.
  - [ ] The `_num` key should not have an underscore (`_`) in it.
  - [ ] There is nothing wrong with the method.

1. How can we call the method in the code below?

  ```javascript
  let myObj = {
    sayHello() {
      return 'Hello there!';
    }
  }
  ```

  - [ ] `myObj().sayHello()`
  - [x] `myObj.sayHello()`
  - [ ] `myObj.sayHello`
  - [ ] `myObj['sayHello']`

1. What are the keys in this object?

  ```javascript
  let apartment = {
    coffeeMaker: 'Aeropress',
    ceilingFan: true,
    books: 114
  }
  ```

  - [ ] `'Aeropress'`, `true`, `114`
  - [x] `coffeeMaker`, `ceilingFan`, `books`
  - [ ] coffeeMaker: `'Aeropress'`, `ceilingFan: true`, `books: 114`

1. What data types can you set as values in an object?

  - [ ] Strings
  - [x] All of the options
  - [ ] Objects
  - [ ] Arrays

1. Which of the following statements is correct?

  - [ ] Objects are containers for variables.
  - [ ] Objects can only store numbers, strings, and booleans.
  - [ ] Objects store data at numbered positions.
  - [x] Objects store data as key/value pairs.

1. How can we access the seatingCapacity value in the restaurant object?

  ```javascript
  let restaurant = {
    name: 'Italian Bistro',
    seatingCapacity: 120,
    hasDineInSpecial: true,
    entrees: ['Penne alla Bolognese', 'Chicken Cacciatore', 'Linguine pesto']
  }
  ```

  - [ ] `restaurant[seatingCapacity]`
  - [ ] `restaurant#seatingCapacity`
  - [x] `restaurant.seatingCapacity`
  - [ ] `restaurant{seatingCapacity}`

1. What number is logged to the console in the following example?

  ```javascript
  let tempObject = {
    num: 2,
    numSquared() {
      num = 3;
      return this.num * this.num;
    }
  };

  console.log(tempObject.numSquared());
  ```

  - [x] 4
  - [ ] 9
  - [ ] 6
  - [ ] 2

1. Which is the correct syntax for an object?

  ```javascript
  // 1
  let myObject = {
    greeting: 'hello'
  };

  // 2
  let myObject = {
    greeting = 'hello'
  };

  // 3
  let myObject: {
    greeting = 'hello'
  };

  // 4
  let myObject; {
    greeting: 'hello'
  };
  ```

  - [ ] 2
  - [x] 1
  - [ ] 3
  - [ ] 4

1. What is a method?

  - [x] A method is a function created inside of an object.
  - [ ] A method is a function that takes an object as its parameter.
  - [ ] A method is a general term used to describe how to create objects.
