**Lab Exercise: Introduction to Variables with Functions**

**Objective:** In this lab, you will learn about variables in JavaScript. You will create a function that assigns values to variables and returns a message using these variables. The result will then be printed to the console using `console.log()`.

**Challenge Goal:** Create a function that takes in two parameters, assigns them to variables, performs a mathematical operation on these variables, and returns the result. Then print this result using `console.log()`.

**Estimated Time to Complete:** 1 hour

**Instructions:**

1. **Create a JavaScript file:**
    - Create a new file `src/variablesAndFunctions.js`.

2. **Create a function that uses variables:**
    - In the newly created file, write a function that declares a variable, assigns a string value to it, and then returns that variable. For example:
        ```javascript
        function getGreeting() {
          let greeting = "Hello, World!";
          return greeting;
        }
        ```
    - Now let's call our function and log its result to the console:
        ```javascript
        console.log(getGreeting());
        ```
    - Save and run your file. You should see "Hello, World!" printed in the console.

3. **Experiment with different variable types:**
    - Create another function that declares a variable and assigns a number to it, and then returns the variable. For example:
        ```javascript
        function getNumber() {
          let number = 5;
          return number;
        }

        console.log(getNumber());
        ```
    - Save and run your file. You should see the number 5 printed in the console.

4. **Challenge Goal:**
    - Now for the challenge. Write a function that takes in two parameters, assigns each to a variable, performs a mathematical operation on these variables, and returns the result. Then print this result using `console.log()`. For example:
        ```javascript
        function addNumbers(num1, num2) {
          let number1 = num1;
          let number2 = num2;
          return number1 + number2;
        }

        console.log(addNumbers(5, 3));
        ```
    - Save and run your file. You should see the number 8 printed in the console.

Congratulations, you've successfully learned about variables in JavaScript and how to use them in functions, and completed this lab!

**Note:** Remember, learning to code is about exploration and trial and error. Don't be afraid to make mistakes and experiment with different ways to use variables in your functions.