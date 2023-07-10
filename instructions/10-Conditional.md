**Lab Exercise: Introduction to Conditional Statements with Functions**

**Objective:** In this lab, you will learn about conditional statements in JavaScript. You will create functions that use conditional statements to make decisions based on different conditions. The returned results will then be printed to the console using `console.log()`.

**Challenge Goal:** Create functions that check if a number is positive, negative, or zero, and return a corresponding message. Then print the results using `console.log()`.

**Estimated Time to Complete:** 1.5 hours

**Instructions:**

1. **Create a JavaScript file:**
    - Create a new file `src/conditionalStatements.js`.

2. **Create a function to check if a number is positive, negative, or zero:**
    
- In the newly created file, write a function that takes a number as a parameter and uses a conditional statement (`if`, `else if`, `else`) to check if the number is positive, negative, or zero. Return a corresponding message based on the condition. For example:
    
```
function checkNumber(number) {
	// TODO: Implement function
}
```

- Now let's call our function with different arguments and log the results to the console:
	  
```javascript
console.log(checkNumber(5));  // "The number is positive."
console.log(checkNumber(-2));  // "The number is negative."
console.log(checkNumber(0));  // "The number is zero."
```

- Save and run your file. You should see the results printed in the console.

**Challenge Goal:**

- Create another function that takes a string as a parameter and uses a conditional statement to check if the string is empty or not. Return a corresponding message based on the condition. For example:

```javascript
function checkString(string) {
  // TODO: Implement function
}
```
        
- Call the `checkString()` function with different arguments and log the results to the console:

```javascript
console.log(checkString("Hello"));  // "The string is not empty."
console.log(checkString(""));  // "The string is empty."
```
        
- Save and run your file. You should see the results printed in the console.

Congratulations, you've successfully learned about conditional statements in JavaScript and how to use them in functions, and completed this lab!

**Note:** Conditional statements are powerful tools for making decisions in your code. Feel free to experiment further by creating more functions that use different conditions and return appropriate results.