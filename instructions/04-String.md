**Lab Exercise: Introduction to String Concatenation with Functions**

**Objective:** In this lab, you will learn about string concatenation in JavaScript. You will create a function that concatenates (joins together) two strings and returns the result. The returned value will then be printed to the console using `console.log()`.

**Challenge Goal:** Create a function that takes two string parameters, concatenates them with a space in between, and returns the result. Then print this result using `console.log()`.

**Estimated Time to Complete:** 1 hour

**Instructions:**

1. **Create a JavaScript file:**
    - Create a new file `src/stringConcatenation.js`.

2. **Create a function that uses string concatenation:**
    - In the newly created file, write a function that declares two string variables, concatenates them, and then returns the result. For example:
        ```javascript
        function greetPerson() {
          let greeting = "Hello,";
          let name = " World!";
          return greeting + name;
        }
        ```
    - Now let's call our function and log its result to the console:
        ```javascript
        console.log(greetPerson());
        ```
    - Save and run your file. You should see "Hello, World!" printed in the console.

3. **Challenge Goal:**
    - Now for the challenge. Write a function that takes in two parameters, both strings, concatenates them with a space in between, and returns the result. Then print this result using `console.log()`. For example:
        ```javascript
        function createSentence(word1, word2) {
          return word1 + " " + word2;
        }

        console.log(createSentence("Hello,", "World!"));
        ```
    - Save and run your file. You should see "Hello, World!" printed in the console.

Congratulations, you've successfully learned about string concatenation in JavaScript and how to use it in functions, and completed this lab!

**Note:** Remember, learning to code involves lots of experimentation and trial and error. Don't be afraid to make mistakes and experiment with different ways to concatenate strings in your functions.