# Quiz: JavaScript Programming Fundamentals

__1. __

    function Star() { //function body };
    var andromeda = new Star();

__How might you visually depict the prototype chain of `andromeda`?__

  - [ ] `andromeda --> Star --> Function.prototype --> Object.prototype --> null`

  - [x] `andromeda --> Star.prototype --> Object.prototype --> null`

  - [ ] `andromeda --> Star.prototype -> Function.prototype --> Object.prototype --> null`

  - [ ] `andromeda --> Star --> Object.prototype --> null`

  __EXPLANATION__

  `andromeda` is an object created by the `new Star()` constructor function call. The immediate `prototype` of an object created by an object constructor is the prototype property that is created automatically when the constructor function is declared: Star.prototype. This property is an object, so the next prototype is `Object.prototype` and then, lastly, `null`.

  ---

__2. Of the choices, select the best example of a working `for` loop head.__

  - [ ] (x = 0; x == 10; x++)

  - [ ] (var i = 0, i < 8, i++)

  - [x] (var k = 33; k >= 23; k--)

  - [ ] (i = 10, i > 1, i - 1)

  __INTERVIEW QUESTION__

  This is a real question that is commonly asked in engineering interviews.

  The for loop has the following syntax:

  for (statement 1; statement 2; statement 3) { //code block to be executed }

  Statement 1 is executed before the loop (the code block) starts. Statement 2 defines the condition for running the loop (the code block). Statement 3 is executed each time after the loop (the code block) has been executed.

  ---

__3. For what values of i is "Oh wow" printed?__

    var i = 14;
    while (i > 4) {
      if (i % 4 === 1) {
        console.log(‘Oh wow’);
      }
      i--;
    }

  - [ ] 1, 7, 11

  - [x] 13, 5, 9

  - [ ] 14, 8, 2

  - [ ] None of the above

  ---

__4.  Which methods ADD elements to an array?__

  - [x] push() and unshift()

  - [ ] push() and pop()

  - [ ] pop() and shift()

  - [ ] unshift() and shift()

  __INTERVIEW QUESTION__

  This is a real question that is commonly asked in engineering interviews.

  CORRECT ANSWERS: The `push()` method can append one or more elements to the end of an array. The `unshift()` method is like the `push()` method, only it works at the beginning of the array. The `unshift()` method can prepend one or more elements to the beginning of an array.

  INCORRECT ANSWERS: The `pop()` method pulls the last element off of the given array and returns it. The `shift()` method is like the `pop()` method, only it works at the beginning of the array. The `shift()` method pulls the first element off of the given array and returns it.

  ---

__5. __

    var val = 4;

    var printVal = function() {
      return 8;
    };

    function printVal() {
      var val = 6;
      return val + 5;
    }

__Which of these values will be returned if we call `printVal()`?__

  - [ ] 4

  - [x] 8

  - [ ] 11

  - [ ] None of the above

  ---

__6. What does this loop do?__

    var array = [3, 4, 6, 23, 23, 9];
    var number = 0;

    for (var i = 0; i < array.length; i++) {
        if (array[i] > number) {
            number = array[i];
        }
    }
    console.log(number);​

  - [ ] It finds the smallest number in the array.

  - [x] It finds the largest number in an array.

  - [ ] It finds if a number occurs more than once in the array.

  - [ ] It does nothing; there is an error in the code.

  __INTERVIEW QUESTION__

  This is a real question that is commonly asked in engineering interviews.

  The loop first checks if the first number in the array is greater than zero. If it is, then that number is assigned to a variable. The loop iterates through each element in the array, checking to see if the next number in the array is greater than the last number saved to the variable. When the loop reaches the last number in the array, we are left with the largest number saved to a variable.

  ---

__7. What is (6 * 4 + 7) % 3?__

  - [x] 1

  - [ ] 3

  - [ ] 10

  - [ ] 28

  __EXPLANATION__

  Following standard order of operations, we first multiply 6 times 4 to get 24, then we add 7 to get 31. 31 divided by 3 is 10, with 1 as a remainder.

  ---

__8.__

    function double(x) { return x * 2; }
    var x = 7;
    double(5);

  __What is the value of `x` after the above code executes?__

  - [ ] 2

  - [ ] 5

  - [x] 7

  - [ ] 14

  __EXPLANATION__

  When the function is called and passed 5 as an argument for `x`, the function returns the number 10. Outside of the function, when we assign the variable `x` a value of 7, this value is not altered by the function call in any way.

  ---

__9. How do you include a JavaScript file in an HTML document?__

  - [x] `<script src='path/to/script.js'></script>`

  - [ ] `<link type='script' src='path/to/script.js'>`

  - [ ] `<script><a href='path/to/script.js'></a></script>`

  - [ ] `<a type='script' src='path/to/script.js'><a/>`

  ---

__10. What is the default value of a variable that is not initialized with a value? e.g. `var myVar;` instead of `var myVar = 6;`__

  - [ ] 0

  - [x] undefined

  - [ ] null

  - [ ] false

  __EXPLANATION__

  All variables declared without a value are given undefined as their value by default.

  ---

__11.__

    function getFunc() {
      var x = 7;
      return function(y) {
        console.log(x+y);
      }
    }
    var f = getFunc();
    f(5);

  __What's logged to the console?__

  - [ ] 5

  - [ ] 7

  - [x] 12

  - [ ] undefined

  __EXPLANATION__

  Once `getFunc()` returns, the anonymous function that prints to the console still has access to the variable `x`.

  `getFunc()` returns a reference to this anonymous function. Later on, we call that function, and it still has access to all of the variables it had access to at the time of creation. All of these variables that the function has access to at its creation create a closure, which sticks around for as long as the function pointer itself does.

  Because of this, when we call f(5), the function is still able to see that a has a value of 7, and it therefore prints 12.
