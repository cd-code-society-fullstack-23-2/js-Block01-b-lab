**Lab Exercise: Introduction to Parameters and Arguments with Functions**

**Objective:** In this lab, you will learn about using parameters and arguments in JavaScript functions. You will create a function that takes parameters and uses them in the function body. The returned value will then be printed to the console using `console.log()`.

**Challenge Goal:** Create a function that takes two string parameters, concatenates them with a space in between, and returns the result. Then print this result using `console.log()`.

**Estimated Time to Complete:** 1.5 hours

**Instructions:**

1. **Create a JavaScript file:**
    - Create a new file `src/parametersAndArguments.js`.

2. **Create a function that takes parameters:**
    - In the newly created file, write a function that takes two string parameters and returns them concatenated with a space in between. For example:
        ```javascript
        function concatenateStrings(string1, string2) {
          return string1 + ' ' + string2;
        }
        ```
    - Now let's call our function with arguments and log its result to the console:
        ```javascript
        console.log(concatenateStrings("Hello,", "world!"));  // "Hello, world!"
        ```
    - Save and run your file. You should see the returned value printed in the console.

3. **Experiment with different arguments:**
    - Try calling your function with different arguments and log the results to the console. For example:
        ```javascript
        console.log(concatenateStrings("Goodbye,", "world!"));  // "Goodbye, world!"
        console.log(concatenateStrings("Hello,", "universe!"));  // "Hello, universe!"
        ```
    - Save and run your file. You should see the new results printed in the console.

Congratulations, you've successfully learned about using parameters and arguments in JavaScript functions, and completed this lab!

**Note:** Learning to code is about exploration and trial and error. Don't be afraid to experiment with passing different arguments to your function.