**Lab Exercise: Introduction to For Loops with Functions**

**Objective:** In this lab, you will learn about for loops in JavaScript. You will create functions that utilize for loops to perform specific tasks. The results will then be printed to the console using `console.log()`.

**Challenge Goal:** Create functions that utilize for loops to perform the following tasks:
1. Print numbers from 1 to a given limit.
2. Calculate the sum of numbers from 1 to a given limit.
3. Print even numbers from 1 to a given limit.
4. Print the elements of an array in reverse order.

**Estimated Time to Complete:** 1.5 hours

## Instructions

**Create a JavaScript file:**

- Open Visual Studio Code.
- Create a new file by clicking on "File" > "New File" or using the shortcut `Ctrl + N`.
- Save this file with a `.js` extension by clicking on "File" > "Save As" or using the shortcut `Ctrl + S`. Choose a directory for your JavaScript labs. You might name the file `forLoops.js`.

**Create a function to print numbers:**

- In the newly created file, write a function named `printNumbers` that takes a single parameter, `limit`.
- Inside the function, use a for loop to iterate from 1 to the given limit (inclusive).
- Print each number to the console using `console.log()`. For example:

```javascript
function printNumbers(limit) {
  let response = "";
  for (let i = 1; i <= limit; i++) {
    response +=i;
  }
  return response;
}
```

**Create a function to calculate the sum:**

- Write another function named `calculateSum` that takes a single parameter, `limit`.
- Inside the function, use a for loop to iterate from 1 to the given limit (inclusive).
- Initialize a variable named `sum` to 0 before the loop.
- Add each number to the `sum` variable during each iteration.
- After the loop, return the calculated `sum`. For example:
    
```javascript
function calculateSum(limit) {
  let sum = 0;
  for (let i = 1; i <= limit; i++) {
    sum += i;
  }
  return sum;
}
```

**Create a function to print even numbers:**

- Write another function named `printEvenNumbers` that takes a single parameter, `limit`.
- Inside the function, use a for loop to iterate from 1 to the given limit (inclusive).
- Use an `if` statement to check if the current number is even (`i % 2 === 0`).
- If the number is even, print it to the console using `console.log()`. For example:

```javascript
function printEvenNumbers(limit) {
	let response = "";
  for (let i = 1; i <= limit; i++) {
    if (i % 2 === 0) {
      response +=i;
    }
  }
  return response;
}

```

**Create a function to print an array in reverse order:**

- Write another function named `printArrayReversed` that takes a single parameter, `arr`.
- Inside the function, use a for loop to iterate from the last index of the array to the first index.
- Print each element to the console using `console.log()`. For example:

```javascript
function printArrayReversed(arr) {
  let response = "";
  for (let i = arr.length - 1; i >= 0; i--) {
    console.log(arr[i]);
  }
  return response;
}
```

**Call the functions with different arguments:**

- Call each function with different arguments and test their functionality.
- For example:

```javascript
let numbers = printNumbers(10);
console.log(numbers);  // Should print numbers from 1 to 5

let sum =calculateSum(5);
console.log(sum);  // Should calculate and return the sum of numbers from 1 to 5

let evenNums = printEvenNumbers(10);
console.log(evenNums);  // Should print even numbers from 1 to 10

let array = printArrayReversed([1, 2, 3, 4, 5]);
console.log(array);  // Should print the elements of the array in reverse order
```

7. **Save and run your file:**
    - Save the file and run it using the command `node forLoops.js`.
    - You should see the expected results printed in the console.

Congratulations, you've successfully learned about for loops in JavaScript and how to use them in functions, and completed this lab!

**Note:** For loops are powerful tools for iterating over a range of values or elements in an array. Feel free to experiment further by creating more functions that utilize for loops for different tasks.