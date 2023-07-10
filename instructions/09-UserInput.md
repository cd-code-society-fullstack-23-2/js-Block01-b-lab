**Lab Exercise: Taking User Input from the Command Line using Functions**

**Objective:** In this lab, you will learn how to take input from a user on the command line using JavaScript functions. You will create functions that prompt the user to enter their name and age, read the input, and then display a personalized greeting message.

**Challenge Goal:** Modify the program to prompt the user for additional information, such as their favorite color or hometown, and display a message that includes all the collected information.

**Estimated Time to Complete:** 1.5 hours

**Instructions:**

1. **Create a JavaScript file:**

   - Open Visual Studio Code.
   - Create a new file by clicking on "File" > "New File" or using the shortcut `Ctrl + N`.
   - Save this file with a `.js` extension by clicking on "File" > "Save As" or using the shortcut `Ctrl + S`. Choose a directory for your JavaScript labs. You might name the file `userInputFunctions.js`.

2. **Define functions to read user input:**

   - In the newly created file, write the following function signatures:

     ```javascript
    const readline = require('readline');

    const rl = readline.createInterface({
      input: process.stdin,
      output: process.stdout
    });

    function askName() {
      return new Promise((resolve) => {
        rl.question("What is your name? ", function(name) {
          resolve(name);
        });
      });
    }
    
     function askAge() {
       // TODO: Implement function
     }

     function collectUserInformation() {
       // TODO: Implement function
     }

     function displayGreeting(user) {
       // TODO: Implement function
     }
     ```

3. **Modify the program to take user input:**

   - Implement the `askName` function to prompt the user to enter their name and return the input.
   - Implement the `askAge` function to prompt the user to enter their age and return the input.
   - Implement the `collectUserInformation` function to call the `askName` and `askAge` functions, and store the returned values in variables.
   - Implement the `displayGreeting` function to receive a `user` object as a parameter and display a personalized greeting message that includes the user's name and age.

4. **Run the program and test with sample input:**

   - Save the file.
   - Open the terminal in Visual Studio Code by clicking on "Terminal" > "New Terminal" or using the shortcut `Ctrl + ` (backtick, usually below the Esc key).
   - In the terminal, navigate to the directory where you saved your JavaScript file.
   - Run the program using the command `node userInputFunctions.js`.
   - Test the program with sample input by providing your name and age.
   - Verify that the program displays a personalized greeting message.

   **Example:**

   ```
   What is your name? John
   What is your age? 25
   Hello, John! You are 25 years old.
   ```

5. **Challenge Goal:**

   - Modify the program to prompt the user for additional information, such as their favorite color or hometown.
   - Add new functions to prompt the user for the additional information and return the input.
   - Update the `collectUserInformation` function to call the new functions, collect all the user information in variables, and return an object with the collected information.
   - Update the `displayGreeting` function to display a greeting message that includes all the collected information.

   **Example Code:**

   ```javascript
   function askColor() {
     // TODO: Implement function
   }

   function askHometown() {
     // TODO: Implement function
   }

   function collectUserInformation() {
     // TODO: Implement function
   }

   function displayGreeting(user) {
     // TODO: Implement function
   }
   ```

6. **Save the file and run the program again:**

   - Run the program using the command `node userInputFunctions.js`.
   - Test the program with sample input by providing your name, age, favorite color, and hometown.
   - Verify that the program displays a greeting message that includes all the collected information.

   **Example:**

   ```
   What is your name? John
   What is your age? 25
   What is your favorite color? Blue
   Where is your hometown? London
   Hello, John! You are 25 years old.
   Your favorite color is Blue.
   Your hometown is London.
   ```

Congratulations, you've successfully learned how to take user input from the command line using JavaScript functions!

**Note:** Taking user input and processing it is a common task in many applications. Feel free to experiment further and enhance the program to gather additional information or perform additional operations on the input.