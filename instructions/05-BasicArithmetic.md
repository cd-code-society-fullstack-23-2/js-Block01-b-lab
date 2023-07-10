**Lab Exercise: Introduction to Basic Arithmetic Operations with Functions**

**Objective:** In this lab, you will learn about basic arithmetic operations in JavaScript. You will create a function that performs an operation on two numbers and returns the result. The returned value will then be printed to the console using `console.log()`.

**Challenge Goal:** Create four functions for addition, subtraction, multiplication, and division. Each function will take two numeric parameters, perform the respective operation, and return the result. Then print the result of each operation using `console.log()`.

**Estimated Time to Complete:** 1.5 hours

**Instructions:**

1. **Create a JavaScript file:**
    - Create a new file `src/basicArithmeticOperations.js`.

2. **Create functions for basic arithmetic operations:**
    - In the newly created file, write functions for addition, subtraction, multiplication, and division. Each function will take two numbers as parameters, perform the respective operation, and return the result.
        For example:
        ```javascript
        const addNumbers = (num1, num2) => {
          return num1 + num2;
        }

        const subtractNumbers = (num1, num2) => {
          return num1 - num2;
        }

        const multiplyNumbers = (num1, num2) => {
          return num1 * num2;
        }

        const divideNumbers = (num1, num2) =>{
          if (num2 === 0) {
            return 'Error: Division by zero is not allowed.';
          }
          return num1 / num2;
        }
        ```
    - Now let's call our functions and log their results to the console:
        ```javascript
        console.log(addNumbers(10, 5));  // 15
        console.log(subtractNumbers(10, 5));  // 5
        console.log(multiplyNumbers(10, 5));  // 50
        console.log(divideNumbers(10, 5));  // 2
        console.log(divideNumbers(10, 0));  // Error: Division by zero is not allowed.
        ```
    - Save and run your file. You should see the results of each operation printed in the console.

Congratulations, you've successfully learned about basic arithmetic operations in JavaScript and how to use them in functions, and completed this lab!

**Note:** Learning to code involves lots of experimentation and trial and error. Don't be afraid to make mistakes and experiment with different operations in your functions.