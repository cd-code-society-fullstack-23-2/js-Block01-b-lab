**Lab Exercise: Experimenting with console.log and Functions**

**Objective:** In this lab, you will experiment with the `console.log()` function and JavaScript functions. The objective is to create functions that return various messages and numbers, and then print these results to the console using `console.log()`.

**Challenge Goal:** Create a function that performs a mathematical operation on two numbers, returns the result, and then print this result using `console.log()`.

**Estimated Time to Complete:** 60 minutes

**Instructions:**

1. **Create a JavaScript file:**
    - Open Visual Studio Code.
    - Create a new file `src/consoleAndFunctions.js`.

2. **Create a function and print its return value:**
    - In the newly created file, write a function that returns a simple message. For example:
        ```javascript
        function getMessage() {
          return "This is my first message.";
        }
        ```
    - Now let's call our function and log its result to the console:
        ```javascript
        console.log(getMessage());
        ```
    - Save and run your file. You should see "This is my first message." printed in the console.

3. **Create a function that returns a number:**
    - Write a function that returns a number, and log this to the console. For example:
        ```javascript
        const getNumber = () => {
          return 5;
        }

        console.log(getNumber());
        ```
    - Save and run your file. You should see the number 5 printed in the console.

4. **Create a function that returns the result of a numeric expression:**
    - Write a function that returns the result of a numeric expression, and log this to the console. For example:
        ```javascript
        const addNumbers = () =>{
          return 5 + 3;
        }

        console.log(addNumbers());
        ```
    - Save and run your file. You should see the number 8 printed in the console.

5. **Challenge Goal:**
    - Now for the challenge. Write a function that takes two numbers as parameters, performs a mathematical operation on them, and returns the result. Then print this result using `console.log()`. For example:
        ```javascript
        const multiplyNumbers = (num1, num2) =>{
          return num1 * num2;
        }

        console.log(multiplyNumbers(5, 3));
        ```
    - Save and run your file. You should see the number 15 printed in the console.

Congratulations, you've successfully experimented with `console.log()` and JavaScript functions, and completed this lab!

**Note:** Remember, coding is about exploration and learning through trial and error. Don't be afraid to make mistakes - they're a key part of the learning process. Keep experimenting with different ways to use `console.log()` and functions in your code.