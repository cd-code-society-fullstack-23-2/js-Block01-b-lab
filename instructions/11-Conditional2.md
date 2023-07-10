**Lab Exercise: Conditional Statements - Exam Grading**

**Objective:** 

In this lab, you will practice using conditional statements in JavaScript. You will create a function that takes a student's exam score as input and assigns a corresponding grade based on the score. The grade will then be printed to the console using `console.log()`.

**Challenge Goal:** Create a function that determines the grade for a given exam score according to the following grading scale:

- Scores above or equal to 90: Grade A
- Scores between 80 and 89: Grade B
- Scores between 70 and 79: Grade C
- Scores between 60 and 69: Grade D
- Scores below 60: Grade F

**Estimated Time to Complete:** 1 hour

## Instructions:

**Create a JavaScript file:**

   - Open Visual Studio Code.
   - Create a new file by clicking on "File" > "New File" or using the shortcut `Ctrl + N`.
   - Save this file with a `.js` extension by clicking on "File" > "Save As" or using the shortcut `Ctrl + S`. Choose a directory for your JavaScript labs. You might name the file `examGrading.js`.

**Create a function to determine the grade:**

- In the newly created file, write a function named `assignGrade` that takes a single parameter, `score`.
- Inside the function, use a series of conditional statements (`if`, `else if`, `else`) to determine the grade based on the score.
- Return the corresponding grade based on the condition. For example:
   
 ```javascript
 function assignGrade(score) {
   // TODO: Implement function
 }
 ```

**Call the function and display the grade:**

- Call the `assignGrade` function with different test scores as arguments and assign the returned value to a variable.
- Print the grade to the console using `console.log()`. For example:

 ```javascript
 let score1 = 85;
 let grade1 = assignGrade(score1);
 console.log("Score:", score1, "- Grade:", grade1);
 
 let score2 = 95;
 let grade2 = assignGrade(score2);
 console.log("Score:", score2, "- Grade:", grade2);
 
 let score3 = 60;
 let grade3 = assignGrade(score3);
 console.log("Score:", score3, "- Grade:", grade3);
 ```

**Save and run your file:**

- Save the file and run it using the command `node examGrading.js`.
- You should see the corresponding grades for the given scores printed in the console.

Congratulations, you've successfully practiced using conditional statements in JavaScript and completed this lab!

**Note:** 

Conditional statements allow you to make decisions based on different conditions in your code. Feel free to experiment further by adjusting the grading scale or adding additional conditions to handle special cases.