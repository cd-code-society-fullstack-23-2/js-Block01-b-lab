**Lab Exercise: Introduction to Multiple Parameters with Functions**

**Objective:** In this lab, you will learn about using multiple parameters in JavaScript functions. You will create a function that takes multiple parameters and uses them in the function body. The returned value will then be printed to the console using `console.log()`.

**Challenge Goal:** Create a function that takes three parameters: a name, an age, and a city. The function should use these parameters to construct a message and return it. Then print this message using `console.log()`.

**Estimated Time to Complete:** 1.5 hours

**Instructions:**

1. **Create a JavaScript file:**
    - Create a new file `src/moreParameters.js`.

1. **Create a function with multiple parameters:**

   Write a function called `createMessage` that takes three parameters: `name`, `age`, and `city`. The function should use these parameters to construct a message and return it. For example:

   ```javascript
   const createMessage = (name, age, city) => {
     // Construct the message using the parameters
     // Return the constructed message
   }
   ```

2. **Call the function and log the result:**

   Call the `createMessage` function with arguments and log the returned message to the console using `console.log()`. For example:

   ```javascript
   console.log(createMessage("John", 25, "New York"));  // Expected output: "My name is John, I am 25 years old, and I live in New York."
   ```

3. **Experiment with different arguments:**

   Try calling the `createMessage` function with different arguments and log the returned messages to the console. For example:

   ```javascript
   console.log(createMessage("Alice", 30, "Los Angeles"));  // Expected output: "My name is Alice, I am 30 years old, and I live in Los Angeles."
   console.log(createMessage("Bob", 22, "London"));  // Expected output: "My name is Bob, I am 22 years old, and I live in London."
   ```

   Feel free to explore and experiment with different arguments to create meaningful messages.

**Note:** Learning to code is about exploration and trial and error. Don't be afraid to experiment with passing different arguments to your function and creating meaningful messages.